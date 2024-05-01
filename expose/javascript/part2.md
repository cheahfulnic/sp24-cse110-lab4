1. The line logs 3, the length of the prices array, to the console. This is because the for loop terminates when i is the length of the array. var allows i to be accessible within the entire function.
   
2. The line logs 150, the discounted price of the third index in the price array, to the console. This is because the for loop terminates when i is the index of the third and last element of the price array. The last operation done on this element was deducting the discount applied to the original price. var allows discountedPrice to be accessible within the entire function.
   
3. The line logs 150, the final price of the third index in the price array, to the console. This is because the for loop terminates when i is the index of the third and last element of the price array. The last operation done on this element is rounding its discounted price to two decimal places. Since the discounted price was already a whole number, the final price remains a whole number. var allows finalPrice to be accessible within the entire function.
   
4. The line returns the discounted array, [50, 100, 150]. The elements are half the value of those in the original prices array since the discount is 0.5/50%. var allows discounted to be accessible within the entire function.
   
5. Error because let is block-scoped and console.log(i) is outside the block that i is defined in (the for loop).
   
6. Error because let is block-scoped and console.log(discountedPrice) is outside the block that discountedPrice is defined in (the for loop).
   
7. The line logs 150, the final price of the third index in the price array, to the console. This is because the for loop terminates when i is the index of the third and last element of the price array. The last operation done on this element is rounding its discounted price to two decimal places. Since the discounted price was already a whole number, the final price remains a whole number. The variable finalPrice is accessible since console.log(finalPrice) is within the same block where finalPrice was defined.
   
8. The line returns the discounted array, [50, 100, 150]. The elements are half the value of those in the original prices array since the discount is 0.5/50%. The variable discounted is accessible since the return statement is within the same block where discounted was defined.
9.  Error because let is block-scoped and console.log(i) is outside the block that i is defined in (the for loop).
    
10. This line logs 3, the length of the prices array, to the console. const allows length to be accessible within the same block, which is the block that console.log(length) is in.
    
11. The line returns the discounted array, [50, 100, 150]. The elements are half the value of those in the original prices array since the discount is 0.5/50%. const allows discounted to be accessible within the same block, which is the block that the return statement is in. The elements in the discounted array are still mutable as the elements themselves aren't const. Only the reference discounted cannot be reassigned to a different array.
    
12. A) student.name
12. B) student['Grad Year']
12. C) student.greeting()
12. D) student['Favorite Teacher'].name
12. E) student.courseLoad[0]

13. '32' since the number 2 maps to its exact string representation.
13. 1 since the string '3' maps to its number representation.
13. 3 since null is treated as 0.
13. '3null' since null maps to its exact string representation.
13. 4 since true is treated as 1.
13. 0 since both false and null are treated as 0.
13. '3undefined' since undefined maps to its exact string representation.
13. NaN since undefined cannot be represented as a number.

14. true since the string '2' maps to its number representation.
14. false since two strings are compared lexicographically.
14. true since the string '2' maps to its number representation.
14. false since they are of different variable types.
14. false since true is treated as 1.
14. false since they are of different variable types, boolean and Boolean object.

15. A strict equality operator === checks the equality without type conversion whereas a regular equality operator == converts operands to numbers before checking equality.

17. The line returns newArr, [2, 4, 6]. We get this by first defining modifyArray as a function that takes an array and callback function as parameters. Then it initializes newArr as an empty set. It then iterates through each element of the array and pushes the return value of the callback function, doSomething, to newArr. Thus, doSomething multiplies each element of the array by two and returns the values.

19. 1, 4, 3, then 2.