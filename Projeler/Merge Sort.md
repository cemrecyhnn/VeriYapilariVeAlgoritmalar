## Merge Sort

 [16,21,11,8,12,22] 

Bu diziyi merge sort algoritması ile sırala.
 Bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüp sıralamayı yaptığımızda sonuç olarak;

 8,11,12,16,21,22 dizinini elde ederiz.


## Big O Gösterimi 

- Diziyi parçalara ayırırken sürekli yarıladık yani 2'ye böldük. Bunun sonucunda 
2^x=n ==> logn kere bölme işlemi yapmış oluruz.
<br>
- Bölünmüş diziyi birleştirirken dizinin uzunluğu olan n kadar birleştirme işlemi yapılır. Bunun sonucunda algoritmanın maliyeti Big O Notasyonunda
 O(n.logn) sonucuna ulaşılır.
Bizim dizimizde eleman sayısı 6 olduğu için sonuç
 6.log6 olacaktır.

