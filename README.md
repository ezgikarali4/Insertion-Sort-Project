# INSERTION-SORT-PROJECT
Patika Dev Profile: https://app.patika.dev/ezgikarali4

## PROJECT 1
[22,27,16,2,18,6] -> Insertion Sort

  1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  2. Big-O gösterimini yazınız.
  3. Time Complexity: 
      -Average case: Aradığımız sayının ortada olması,
      -Worst case: Aradığımız sayının sonda olması, 
      -Best case: Aradığımız sayının dizinin en başında olması.
  4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


### 1. INSERTION SORT

İlk başlayacağımız sayı listenin başındaki sayı olduğundan dolayı 22'den başlarız ve sağına "|" işaretini çekeriz. Sonra da işaretin sağında kalan ifade ile karşılaştırız. Sağdaki sayı küçük ise "|" işaretinin soluna geçirtilerek solundaki küçük ve sağındaki büyük sayı olacak şekilde sıralanır. Eğer sayı büyük ise "|" işaretinin solundaki sayının sağına yazılır.

Since the first number we will start with is the number at the beginning of the list, we start from 22 and "|" to the right. We draw the sign. Then we compare it with the expression to the right of the sign. "|" if the number on the right is small It is placed to the left of the sign and sorted as the small number on the left and the large number on the right. "|" if number is large It is written to the right of the number to the left of the sign.

[22|, 27, 16, 2, 18, 6] 
[22, 27|, 16, 2, 18, 6]
[16, 22, 27|, 2, 18, 6] 
[2, 16, 22, 27|, 18, 6] 
[2, 16, 18, 22, 27|, 6] 
[2, 6, 16, 18, 22, 27]

### 2. BIG-O 

Best case    : O(n)
Average case : O(n^2)
Worst case   : O(n^2)

### 3. TIME COMPLEXITY
Average case: The number we are looking for is in the middle.
Worst case: The number we are looking for is at the end.
Best case: The number we are looking for is at the beginning.

### 4. Which case will 18 be taken from after the series is sorted? Write.
Average case -> [2, 6, 16, 18, 22, 27]

### [7,3,5,8,2,9,4,15,6] 
Write the first 4 steps of the array according to the Insertion Sort.

First step: [7| , 3, 5, 8, 2, 9, 4, 15, 6]
Second step: [3, 7| , 5, 8, 2, 9, 4, 15, 6]
Third step: [3, 5, 7| , 8, 2, 9, 4, 15, 6]
Fourth step: [3, 5, 7, 8| , 2, 9, 4, 15, 6]
