# Data-Structure

IMPORTANT LINK :- https://www.bigocheatsheet.com/

Big O notation :- Big O notation is language we use to find out how long some code or alogorithm takes to run.
Why Big O is important :- it use to write scalable code. 
Below is image for big o complexity chart. 
 
![image](https://user-images.githubusercontent.com/15019052/146667373-026f722d-80e0-4f12-a1cb-68e22f94f551.png)

1. Linear Time:- Numer of element increases opration increases. O(n) runing on each element from array if element count increases oprations will also get increase. For example if array has one element it take only one loop to iterate so big O notation is O(1) while if we have 1000 element in array to iterate it takes O(1000) => O(n)
2. constant Time O(1):- number of opration required is one.

Simplefying Big O :- 
Rule 1:- worst case :- It means we have consider while looping through array we need to go through all items in it.
Rule 2: Remove constant :- Drop constant for example if we have Big O as O(n/2 + 100) we can simplefy this to O(n).
Rule 3: Different terms for input :- If function accepting two different array parameter and we are looping seperatly through each array then Big O is O(param1 * param2)
Rule 4: Drop non Dominants: If we have Big O (n + n^2) then we drop non dominants part which is n so it becomes Big O(n^2)
