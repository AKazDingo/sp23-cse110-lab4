# Part 2

1. Line 12 will output "3", because the variable i was stored as a var. This means that the variable continues to exist outside of any specific scope and after the for loop ended. The loop went until i wasn't less than prices.length, which had a length of 3.

2. Line 13 will output "150", because the variable discountedPrice was stored as a var. This means that the variable continues to exist outside of any specific scope and after the for loop ended. The final value of discountedPrice was set to the last value in prices (300) multiplied by the discount of 0.5, resulting in 150.

3. Line 14 will output "150". The final value of finalPrice was set by the rounded final value of discountedPrice, which was 150.

4. The function returns [50, 100, 150], which is the list 'discounted' of the calculated discounted prices.

5. Error, as the scope of i is limited to the for loop it was initialized in.

6. Error, as the scope of discountedPrice is limited to the for loop it was initialized in.

7. Line 14 will output "150". finalPrice was declared within scope and its value was assigned in the last loop of the for loop, being 150.

8. The function returns [50, 100, 150], which is the list 'discounted' of the calculated discounted prices.

9. Error, as the scope of i is limited to the for loop it was initialized in.

10. Line 12 will output "3". The value of length was declared within scope and was not modified, being set to the length of the list 'prices'.

11. The function returns [50, 100, 150], which is the list 'discounted' of the calculated discounted prices.

12. Notation for:
    * A: **student.name**
    * B: **student["Grad Year"]**
    * C: **student.greeting()**
    * D: **student['Favorite Teacher'].name**
    * E: **student.courseLoad[0]**

13. Arithmetic:
    * A: **'32'**, one of the data types was a string, making the **+** symbol perform concatenation
    * B: **1**, the **-** symbol performs numerical subtraction, converting the string to its contained integer value
    * C: **3**, null converts to an integer value of 0
    * D: **'3null'**, null converts to a string value of 'null'
    * E: **4**, true converts to an integer value of 1
    * F: **0**, false and null both convert to their integer values of 0
    * G: **'3undefined'**, undefined converts a string value of 'undefined'
    * H: **NaN**, the **-** symbol performs numerical subtraction, converting the string to the contained integer value. Subtracting by undefined results in NaN (Not a Number)

14. Comparison:
    * A: **true**, because types being compared are different, '2' is converted to a number and 2 is greater than 1
    * B: **false**, in a comparison between strings the value of the first character in both is compared, if equal then it goes to the next character of both strings. The character '2' is greater than the character '1', therefore it is false.
    * C: **true**, because types being compared are different, '2'  is converted to a number and 2 == 2;
    * D: **false**, a strict equality operator invoked on different types is always false
    * E: **false**, because types being compared are different, true is converted to its numerical form 1, and 1 != 2
    * F: **true**, Boolean(2) is true because any non zero number is considered true. The strict equality operator then evaluated true === true, which is true.

15. == is an equality operator that converts compatible types to numbers, whereas === is a strict equality operator that checks equality without type conversion. === will always return a false if objects of different types are compared.

16. See part2-question16.js

17. The result that will be returned will be an array that is [2,4,6], as it called the function doSomething on each of the values in the input array and made a new array with those new values. doSomething returns 2 times whatever number is input, and our callback parameter is set to doSomething, making an array with double each of the values of our initial array.

18. See part2-question18.js

19. The output will be: 1 4 3 2. This order can be explained by the fact that 1 and 4 are just simple output commands, but 3 and 2's output was made with the 'setTImeout' function with a delay of 1000 and 0 respectively. Even with the delay of 0ms, 3 was still output after 4, and the delay of 1000ms for 2 caused to to be output 1 second after the rest.
