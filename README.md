# INSERTION SORT ÖDEVİ
***
## Veri:[22,27,16,2,18,6]
***
### Insertion S. türüne göre aşamaları aşağıdaki gibidir.

```
[22,27,16,2,18,6] 
```
```
->[16,22,27,2,18,6]  
```
```
-->[2,16,22,27,18,6]
```
```
--->[2,16,22,27,18,6]   
```

```
--->[2,16,18,22,27,6] 
```

```
--->[2,6,16,18,22,27] 
```
***

### BİG-O göre gösterimi aşağıdaki gibidir
n+(n-1)+(n-2)+(n-3)..+1=(n2+n)/2 worst case o(n2)
***

### 18 sayısı hangi case kapsamına girer?
Avarage Case olarak tanımlanır

***
##Veri: [7,3,5,8,2,9,4,15,6]

```
[7,3,5,8,2,9,4,15,6]
```
```
->[(2,3),5,8,7,9,4,15,6]
```
```
-->[(2,3,4),8,7,9,5,15,6]
```
```
--->[(2,3,4,5),7,9,8,15,6]
```
