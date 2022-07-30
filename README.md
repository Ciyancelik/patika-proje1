# patika-proje1


[22, 27, 16, 2, 18, 6] -> Insertion Sort

1.	Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

a.	[22, 27, 16, 2, 18, 6] - (n)
b.	[2|, 27, 16, 22, 18, 6] - (n-1)
c.	[2, 6|, 16, 22, 18, 27] - (n-2)
d.	[2, 6, 16|, 18, 22, 27] - (n-3)


2.  Big-O gösterimini yazınız.

 - Time complexity bir algoritmanın çalışması için gerekli olan süredir.
 - Time complexity bize bir algoritma için 3 durum sunar. Best-case, average-case ve worst-case.
 
  - Best-case: Algoritmada yürütme zamanı, maliyet ve karmaşıklık hesaplanırken en iyi sonucun elde edildiği duruma denir.
 
   - Best Case: O(n)

 - Worst-case: Adında da anlaşılacağı gibi best case durumunun tam tersidir. Olabilecek en olumsuz koşulları içinde barındıran durumdur.
  
   - Worst Case: O(n²) = n+(n-1)+(n-2)....+1
    
 - Tahmin ettiğiniz gibi sonuçları en kötü olan durum ile en iyi durum arasında çıkan durumdur. Ortalama bir değerdir.
    
  -  Average Case: O(n²)


3.  Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

    -Worst Case: [27, 22, 18, 16 ,6, 2]
    
    -Average Case: [16, 22, 2, 6, 18, 27]

    -Best Case: [2, 6, 16, 18, 22, 27]

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


    [2|, 3, 5, 8, 7, 9, 4, 15, 6]

    [2, 3|, 5, 8, 7, 9, 4, 15, 6]

    [2, 3, 4|, 8, 7, 9, 5, 15, 6]

    [2, 3, 4, 5|, 7, 9, 8, 15, 6]






