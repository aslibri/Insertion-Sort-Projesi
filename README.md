# Insertion-Sort-Projesi
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1-
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

2- O(n^2) --> n+(n-1)+(n-2)+...+1 = (n*(n-1))/2 --> ((n^2)-n)/2 Dominan değer alınıyor n^2

3- Worst case: aranan sayının sonda olması n kere işlem yaptıracağından 6 n
  Average case: 3 n/2
  Best case: 1 
  
4- Average case e girer.

[7,3,5,8,2,9,4,15,6] -> Insertion Sort

1.Adım :[2,3,5,8,7,9,4,15,6]
2.Adım :[2,3,4,8,7,9,5,15,6]
3.Adım :[2,3,4,5,7,9,8,15,6]
4.Adım :[2,3,4,5,6,9,8,15,7]
