# Insertion Sort

[22,27,16,2,18,6]->

Yukarıdaki diziyi sort türüne göre aşamalarını yazınız.
[2,6,16,22,18,27]
[2,6,16,22,18,27]
[2,6,16,18,22,27]-> insertion sort türüne göre sonuç

-----
### Big-O gösterimini yazınız.

Big O gösterimi : (n-1)+(n-2)+(n+3)+...+1 = (n(n-1))/2 = n^2 
 ##### Sonuç : O(n^2)
-----
### Time Complexity

 Dizi sıralandıktan sonra 18 sayısı dizinin ortalarında olduğu için Average Case kapsamına girer

-----

#### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6] 
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]  
