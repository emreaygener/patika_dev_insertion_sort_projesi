# patika_dev_insertion_sort_projesi
[Patika.dev](https://www.patika.dev/tr)

Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]-->initial step
[2|,27,16,22,18,6]-->1st step
[2,6|,16,22,18,27]-->2nd step
[2,6,16|,22,18,27]-->3rd step
[2,6,16,18|,22,27]-->4th step
[2,6,16,18,22|,27]-->5th step
[2,6,16,18,22,27]-->final step

Big-O gösterimini yazınız.
O(n^2)

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Average Case: data is in mixed order like the given initial state
Worst Case: Data is in descending order, ex: [27,22,18,16,6,2]
Best Case: Data is in ascending order, ex:[2,6,16,18,22,27]

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
this array was an average case example.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]
[2|,3,5,8,7,9,4,15,6]
[2,3|,5,8,7,9,4,15,6]
[2,3,4|,8,7,9,5,15,6]
[2,3,4,5|,7,9,8,15,6]

by Emre Aygener
