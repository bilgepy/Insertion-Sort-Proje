# Insertion-Sort-Proje

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  
	1. aşama = [22, 27, 16, 2, 18,6]    (n)
	2. aşama = [2, 27, 16, 22, 18, 6]   (n-1)
	3. aşama = [2, 6, 16, 22, 18, 27]   (n-2)
	4. aşama = [2, 6, 16, 18, 22, 27]   (1)

Big-O gösterimini yazınız.

  n + (n-1) + (n-2) + 1 = (n.(n+1))/2 = (n^2+n)/2
  Big-O Notation = O(n2)


Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

	Average case: 16, 18
	Worst case: 27
	Best case: 2

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

  Average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

	1. aşama = [7, 3, 5, 8, 2, 9, 4, 15, 6]   (n)
	2. aşama = [2, 3, 5, 8, 7, 9, 4, 15, 6]   (n-1)
	3. aşama = [2, 3, 4, 8, 7, 9, 5, 15, 6]   (n-2)
	4. aşama = [2, 3, 4, 5, 7, 9, 8, 15, 6]   (n-3)

