1. 3 will be logged because i=3 at the end of the for loop above this line. The variable i was declared with var so it exists throughout the function, and this line is still in the function.
2. 150 would be logged because the last time time discountedPrice is initialized is in the last iteration of the for loop, and it exists throughout the function because it was declared with var.
3. 150 would still be logged cause the last time finalPrice is reassigned is in the last iteration of the for loop, and it is declared earlier with var so it exists in the whole function.
4. This function would return the array [50, 100, 150]. There is a for loop within the function that applies the discount to each price in the array passed in and adds it to the array to be returned. The array and the variables declared in the function are declared with the var keyword so they exist throughout the function.
5. This code would cause an error because the variable i is declared in the above for loop with let, meaning that its scope is limited to the for loop. Because here the code tried to access i outside the for loop, it does not exist there and causes an error.
6. This code would cause an error. The variable discountedPrice is declared in the for loop with the let keywork, so it only exists within the for loop. This line tries to access it outside the for loop so it would cause an error.
7. This line would print the last finalPrice(150) from the for loop above. There would not be an error because finalPrice is declared with let at the beginning of the function, so finalPrice's scope is the whole function.
8. This function would return the array [50,100,150]. There is a for loop within the function that applies the discount to each price in the array passed in and adds it to the array to be returned. The array discounted is declared at the beginning of the function with the let keyword so it exists throughout the function and can be added to and returned.
9. This line would cause an error because i is declared in the for loop using the keyword let, so it only exists within the for loop and cannot be accessed outside of it(this line is outside the for loop).
10. This line would print the length of the array prices(3) because the variable length is declared with const at the beginning of the function so it exists throughout the function.
11. This code would cause an error because the array discounted is declared with the const keyword, and later in the function, the code tries to modify it when it cannot be modified.
12. Notation: <br>
A. student.name <br>
B. student["Grad Year"] <br>
C.  student.greeting() <br>
D. (student["Favorite Teacher"]).name <br>
E. (student.courseLoad)[0] <br>
13. Arithmetic <br>
A. '32' because the integer 3 maps to '3' <br>
B. 1 because '3' maps to the integer 3 <br>
C. 3 because null would map to the integer 0 <br>
D. '3null' because null would map to the string 'null' <br>
E. 4 because true would map to 1 <br>
F. 0 because false maps to 0 <br>
G. '3undefined' because 3 maps to '3' <br>
H. Nan because cannot subtract a string <br>
14. Comparison <br>
A. True because '2' mapped to the integer 2 which is greater than 1 <br>
B. False because strings are compared letter by letter and '2' would be greater than '1' <br>
C. True because 2 would map to '2' so they would be equal <br>
D. False because there is no type conversion so they are not equal <br>
E. False because true maps to 1 which is not equal to 2 <br>
F. True because the 2 is converted to Boolean as true which is then equal to true even without type conversion
15. == checks equality with type conversion, while === checks equality without type conversion.
17. The result would be the array [2, 4, 6]. First the array and function are passed in and a new array is created. Then the for loop iterates through the array that was passed in. In each iteration, it calls the function passed in on each element of the array then adds the result to the new array. In this case each element of the array is doubled by the function. Lastly, the new array is returned.
19. 1 is printed, then after a second, 2 is printed, then immediately 3 is printed, then 4 is printed.
