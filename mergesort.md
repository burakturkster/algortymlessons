# MERGE SORT ÖDEVİ
***
## Veri:[16,21,11,8,12,23]
***
### Merge S. türüne göre aşamaları aşağıdaki gibidir.

```
[16,21,11,8,12,23] 
```
Merge sort iki parçaya ayırıyoruz. Tek tek inceleyelim ardından birleştiricez.
İlk parçamız
```
->[16,21,11]
[16,21] - [11] olarak ikiye ayırdık ardından merge ederek en soldaki rakamlara bakılarak
[11,16,21]
```

İkinci Parçamız
```
-->[8,12,22]
[8,12] - [22] olarak ikiye ayırdık ardından merge ederek en soldaki rakamlara bakılarak
[8,12,22]
```
```
Son olarak sol baştan başlayarak sıralamamız
[8,11,12,16,21,22]
```

***

### BİG-O göre gösterimi aşağıdaki gibidir
o(nlogn)
***
 
