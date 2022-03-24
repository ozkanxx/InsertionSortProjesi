# InsertionSortProjesi

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Kaynak : [Patikadev ](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje)

## Cozum,

* Insertion Sort -> ilk elemanin kendinden kucuk deger bulunca onunla yer degistiri. 2. elemana gelince kendisinde kucuk deger buldugu zaman onun yine yer degirtir. Buna gore cozum.


*1. Adım. [7,3,5,8,2,9,4,15,6] 1. elemanimiz 7 ondan en kucuk eleman 2 dir 7 ile 2 yer degistirir. ve sonuc = [2,3,5,8,7,9,4,15,6]

*2. Adım. [2,3,5,8,7,9,4,15,6] 2. elemanimiz 3 ondan en kucuk eleman 3 dir sabit kalır ve sonuc = [2,3,5,8,7,9,4,15,6]

*3. Adım. [2,3,5,8,7,9,4,15,6] 3. elemanimiz 5 ondan en kucuk eleman 4 dir 5 ile 4 yer degistirir. ve sonuc = [2,3,4,8,7,9,5,15,6]

*4. Adım. [2,3,4,8,7,9,5,15,6] 4. elemanimiz 8 ondan en kucuk eleman 5 dir 8 ile 5 yer degistirir. ve sonuc = [2,3,4,5,7,9,8,15,6]
