# ALGORITMA-ALISTIRMA-0306260038
https://www.skillcamp.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje
Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
    Average case: Aradığımız sayının ortada olması
    Worst case: Aradığımız sayının sonda olması
    Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
*****************************************

SORU1 INSERTION SORT
Başlangıç Dizisi:
22,27,16,2,18,6
A1: 22,27,16,2,18,6
A2: 16,22,27,2,18,6
A3: 2,16,22,27,18,6
A4: 2,16,18,22,27,6
A5: 2,6,16,18,22,27
A6: 2,6,16,18,22,27
BigO Değerleri:
Best Case    : O(n). | Average Case : O(n2). | Worst Case   : O(n2).
18 Sayısının Durumu: Average Case.

xxxxxxxxxxxxxxxxxx

SORU 2 - SELECTION SORT
Başlangıç Dizisi: 7,3,5,8,2,9,4,15,6
1. Adım:    2,3,5,8,7,9,4,15,6
2. Adım:    2,3,5,8,7,9,4,15,6
3. Adım:    2,3,4,8,7,9,5,15,6
4. Adım:    2,3,4,5,7,9,8,15,6

********************************************************************************

https://www.skillcamp.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje
Proje 2
16,21,11,8,12,22 -> Merge Sort
    Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    Big-O gösterimini yazınız.

*******************

PROJE 2
MERGE SORT
Başlangıç Dizisi:
16,21,11,8,12,22
Bölme Aşamaları:
16,21,11 8,12,22
16 21,11 8 12,22
16 21 11 8 12 22
Birleştirme Aşamaları:
11,21
12,22
11,16,21
8,12,22
8,11,12,16,21,22
Sonuç:
8,11,12,16,21,22

BigO Değerleri:
Best Case    : O(n log n)
Average Case : O(n log n)
Worst Case   : O(n log n)

********************************************************************************

https://www.skillcamp.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje
Proje 3:
7,5,1,8,3,6,0,9,4,2 dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root xdir,rootun sağından y,Solunda z vb.

*************************************

PROJE 3
BINARY SEARCH TREE
Dizi:
7,5,1,8,3,6,0,9,4,2

Root düğümü 7dir.

5,7den küçük olduğu için 7nin solunda.

1,7den küçük olduğu için sola.
1,5ten küçük olduğu için 5in solunda.

8,7den büyük olduğu için 7nin sağında.

3,7den küçük olduğu için sola.
3,5ten küçük olduğu için sola.
3,1den büyük olduğu için 1in sağında.

6,7den küçük olduğu için sola.
6,5ten büyük olduğu için 5in sağında.

0,7den küçük olduğu için sola.
0,5ten küçük olduğu için sola.
0,1den küçük olduğu için 1in solunda.

9,7den büyük olduğu için sağa.
9,8den büyük olduğu için 8in sağında.

4,7den küçük olduğu için sola.
4,5ten küçük olduğu için sola.
4,1den büyük olduğu için sağa.
4,3ten büyük olduğu için 3ün sağında.

2,7den küçük olduğu için sola.
2,5ten küçük olduğu için sola.
2,1den büyük olduğu için sağa.
2,3ten küçük olduğu için 3ün solunda.

Binary Search Tree:

      7
    /   \
   5     8
  / \     \
 1   6     9
/ \
```

0   3
/ 
2   4


