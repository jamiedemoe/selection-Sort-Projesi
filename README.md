# selection-Sort-Projesi
[22,27,16,22,18,6] --> Selection Sort
## Selection Sort
* [2,27,16,22,18,6] --> en küçük sayımızı buluyoruz ve diğer sayılarla yer değiştiriyoruz. (n tane eleman)
* [2,6,16,22,18,6] -->  sonrasında tekrar küçük sayımızı buluyoruz ver bir sonraki sayı ile yerini değişiyoruz. (n-1)
* [2,6,16,18,22,27] --> en küçükten en büyüğe doğru sıralanmış oldu.

# Big-O Gösterimi
ilk adımda n tane elaman, ikinci adımda (n-1) eleman, üçüncü adımda (n-2) elaman olarak 1 e gelene kadar alıyoruz.
*formül --> n+(n-1)+(n-2)+...+1=n(n+1)/2

* n(n+1)/2 bize n^2+n/2 verir.
* bu sonuçtan n^2 yi alıyoruz.

* sonuç--> o(n^2)

# Time Complexity
 18 sayısı asağıdakilerden hangi case'e girer?
* [2,6,16,18,22,27] dizisi ile 18 elemanı ortaya geldiğinden Average Case'e girmiş oluyor.


## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
*  adım  1 --> [2,3,5,8,7,9,4,15,6] --> 2 ve 7 yer değitirir.
*  adım 2 --> [2,3,4,8,7,9,5,15,6] --> 3 yerinde ancak 5 ile 4 yer değiştirir.
*  adım 3 --> [2,3,4,5,7,9,8,15,6] --> 5 ile 8 yer değiştirir.
*  adım 4 --> [2,3,4,5,6,9,8,15,7] --> 7 ile 6 yer değiştirir.


  **şeklinde 4 adımda gelinebilecek selection sort'a göre sıralanışı bu şekildedir.**
