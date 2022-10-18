# Veri Yapilari ve Algoritmalar Kursu Bitirme Projesi

## Merge Sort Projesi

Proje 2

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

## CEVAPLAR

1. Merge Sort Asamalari?
* Adim 1= [16,21,11] - [8,12,22]$
* Adim 2= [16] - [21,11] - [8] - [12,22]
* Adim 3= [16] - [21] - [11] - [8] - [12] - [22] Her sayi tek kalacak sekilde bölündü. Simdi tekrar birlestirme yapilirken siralama islemi yapilacak.
* Adim 4= [16] - [11,21] - [8] - [12,22] Örnegin burada 16 ile 11 sayisi karsilastirilir ve 11 kücük oldugu icin basa yazilir. Sonra 16 ile 21 sayisi karsilastirilir ve 16 kucuk oldugu icin ikinci siraya yazilir ve 21 sayisi da ücüncü siraya yazilir. Ayni anda diger bölmelerde de ayni islemler yapilir.
* Adim 5= [11,16,21] - [8,12,22] 
* Adim 6= [8,11,12,16,21,22] Son asama.


2. Big-O Gösterimi?

Her kademe de n kadar sayi oldugu icin burdan n geliyor. Her seferinde ikiye bolunerek bir alt kademeye gecis yapildigi icin de burdan 2^x=n den logn geliyor. Big-O = O( n*logn)

[www.patika.dev](https://www.patika.dev/)
