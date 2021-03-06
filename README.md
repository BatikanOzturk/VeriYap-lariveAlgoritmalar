# Veri Yapıları ve Algoritmalar

Patika.dev Veri Yapıları ve Algoritmaları dersini bitirme projesidir.

# Insertion Sort

  *  [22,27,16,2,18,6] -> Insertion Sort
  *  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  *  Big-O gösterimini yazınız.
  *  Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
  *  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
  *  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
[22|,27,16,2,18,6]
[22,27|,16,2,18,6]
[16,22,27|,2,18,6]
[2,22,16,27|,18,6]
[2,22,16,18,27|,6]
[6,2,22,16,18,27]
```

### Big O Notation Gösterimi

```
Worst Case : O(n^2)
Avarage Case : O(n^2)
Best Case : O(n)
```

### Time Complexity

```
Best Case: [6,2,22,16,18,27]
Worst Case: [27,22,18,16,6,2]

```

### 18 Sayısının Case Durumu

```
Dizi sıralandıktan sonra [2,6,16,18,22,27] halini alır.Bu durumda 18 sayısı ortada olarak sayılabilir.
Bu nedenle avarage case kapsamında yer alır.
```

### [7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı

```
[7|,3,5,8,2,9,4,15,6]
[3,7|,5,8,2,9,4,15,6]
[3,5,7|,8,2,9,4,15,6]
[3,5,7,8|,2,9,4,15,6]

```

# Merge Sort

* [16,21,11,8,12,22] -> Merge Sort
* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

```
[16,21,11|,8,12,22]
[16,21,11] [8,12,22]
[16] [21,11]  [8] [12,22]
[16] [11,21]  [8] [12,22]
[11,16,21]  [8,12,22]
[8,11,12,16,21,22]
```
### Big O Notation Gösterimi

```
Worst Case : O(n*logn)
Avarage Case : O(n*logn)
Best Case : O(n*logn)
```
# Binary Search Tree

* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Root: 7 ' dir.

Rootun sağında: 8,9
Rootun solunda: 0,1,2,3,1,5,6

```

```
7
```

```
  7
 /
6
```

```
   7
  / \
 5   8
```

```
    7
   / \
  5   8
 / \
1   6

```

```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
```

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
      
```