# Insertion Sort Odev

[22,27,16,2,18,6] -> Insertion Sort

## 1-> Sıralama
- [22,27,16,2,18,6] 22 sayısını ele alarak karşılaştıracağız.
- [2,27,16,22,18,6] En küçük sayı olan 2'yi buldu ve 22 ile yer değiştirdi.Şimdi 27 sayısını ele alacağız.
- [2,6,16,22,18,27] 6'yı buldu ve 27 ile yer değiştirdi.Şimdi 16 sayısını ele alacağız.
- [2,6,16,22,18,27] 16 zaten olması gereken yerde imiş ve değişme olmadı.Şimdi 22 sayısını ele alacağız.
- [2,6,16,18,22,27] 18'i buldu ve 22 ile yer değiştirdi.Şimdi 22 sayısını ele alacağız.
- [2,6,16,18,22,27] 22 zaten olması gereken yerde imiş ve değişme olmadı.27 sayısı da olması gereken yerde imiş.

## 2-> Big O Gösterimi
- ilk elemanı bulurken n kere arama yaparız
- ikinci elemanı bulurken n-1 kere arama yaparız.
- ucuncu elemanı bulurken n-2 kere arama yaparız.
             .
             .
             .
- son elemanı bulurken 1 kere arama yaparız.

- n+n-1+n-2+n-3+...+1 ->> n.(n+1)/2=n^2+n/2 ->> **O(n^2)

## 3-> Time Complexity
- Average Case: Aradığımız sayının ortada olması **O(n^2)
- Worst Case: Aradığımız sayının sonda olması **O(n^2)
- Best Case: Aradığımız sayının dizinin en başında olması **O(n)

## 4->
- [2,6,16,18,22,27] 18 sayısı ortada oldugundan Average Case'dir.


- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
- [7,3,5,8,2,9,4,15,6] 7 sayısını ele alarak karşılaştıracağız.
- [2,3,5,8,7,9,4,15,6] En küçük sayı olan 2'yi buldu ve 7 ile yer değiştirdi.Şimdi 3 sayısını ele alacağız.
- [2,3,5,8,7,9,4,15,6] 3 zaten olması gerektiği yerde imiş. Şimdi 5 sayısnı ele alacağız.
- [2,3,4,8,7,9,5,15,6] 4'ü buldu ve 5 ile yer değiştirdi. Şimdi 8 sayısını ele alacağız.
- [2,3,4,5,7,9,8,15,6] 5'i buldu ve 8 ile yer değiştirdi. Şimdi 7 sayısını ele alacağız.
- [2,3,4,5,6,9,8,15,7] 6 sayısını buldu ve 7 ile yer değiştirdi. Şimdi 9 sayısını ele alacağız.
- [2,3,4,5,6,7,8,15,9] 7 sayısını buldu ve 9 ile yer değiştirdi. Şimdi 8 sayısını ele alacağız.
- [2,3,4,5,6,7,8,15,9] 8 zaten olması gerektiği yerde imiş. Şimdi 15 sayısını ele alacağız.
- [2,3,4,5,6,7,8,9,15] 9 sayısını buldu ve 15 ile yer değiştirdi. 15 zaten olması gerektiği yerde.