# insertion-sort-projection
[22,27,16,2,18,6]

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

2. Big-O gösterimini yazınız.
(n.(n+1))/2
(n^2+n)/2
O(n^2)

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Average Case: O(logn)
Worst Case: O(n^2)
Best Case: O(nlogn)

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
Dizi sıralandıktan sonra: [2,6,16,18,22,27]
18 sayısı ortada olduğu için Average Case kapsamına girer.

[7,3,5,8,2,9,4,15,6]
1. [2,3,5,8,7,9,4,15,6] (n)
2. [2,3,4,8,7,9,5,15,6] (n-1)
3. [2,3,4,5,7,9,8,15,6] (n-2)
4. [2,3,4,5,6,9,8,15,7] (n-3)
