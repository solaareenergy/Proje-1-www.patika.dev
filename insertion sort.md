# PROJE 1 - insertion sort
## 1.SORU
[ 22,27,16,2,18,6 ] -> insertion sort (en basit siralama)
1. [ 2,27,16,22,18,6 ]  n sayida islem yapti
2. [ 2,6,16,22,18,27 ]  (n-1) sayida islem yapti
3. [ 2,6,16,18,22,27 ]  (n-2) sayida islem yapti ........ + 1 sayida islem yapti

## 2.SORU
                      Big-O icin n+(n-1)+(n-2)+...... + 1 işlem yapmali
                      Big-O   =  1+2+3+...+(n-2)+(n-2)+n = (n^2+n)/2  ise O(n)=n^2 dir.

## 3.SORU
[ 22,27,16,2,18,6 ] dizisinin "18" elemani sonda veya basta olmadigi icin 'Avarage case' kapsamina girer.

## 4.SORU
[ 7,3,5,8,2,9,4,15,6 ] -> Selection sort ilk dört adım
1. Adım [ 2,3,5,8,7,9,4,15,6 ]
2. Adım [ 2,3,5,8,7,9,4,15,6 ]
3. Adım [ 2,3,4,8,7,9,5,15,6 ]
4. Adım [ 2,3,4,5,7,9,8,15,6 ]