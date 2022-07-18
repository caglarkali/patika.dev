## Proje 3
----

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

**Örnek:** root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


````
           7
          / \
         5   8
        / \   \
       1   6   9
      / \
     0   3                            
        / \
       2   4     
````       

1. Aşama: Root 7'dir.
2. Aşama: 5 sayısı 7'den küçüktür, root'un solunda bulunur.
3. Aşama: 1 sayısı 7 ve 5'ten küçüktür, 5'in solunda bulunur.
4. Aşama: 8 sayısı 7'den büyüktür, 7'nin sağında bulunur.
5. Aşama: 3 sayısı 7 ve 5'ten küçük 1'den büyüktür, 1'in sağında bulunur.
6. Aşama: 6 sayısı 7'den küçük 5'ten büyüktür, 5'in sağında bulunur.
7. Aşama: 0 sayısı 7,5 ve 1'den küçüktür, 1'in solunda bulunur.
8. Aşama: 9 sayısı 7 ve 8'dan büyüktür, 8'in sağında bulunur.
9. Aşama: 4 sayısı 7 ve 5'ten küçüktür 1'den ve 3'ten büyüktür, 3'ün sağında bulunur.
10. Aşama: 2 sayısı 7 ve 5'ten küçük, 1'den büyük ve 3'ten küçüktür. 3'ün solunda bulunur.
    

