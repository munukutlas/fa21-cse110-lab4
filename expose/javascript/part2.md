1. 3 will be logged because i=3 at the end of the for loop above this line. The variable i was declared with var so it exists throughout the function, and this line is still in the function.
2. 150 would be logged because the last time time discountedPrice is initialized is in the last iteration of the for loop, and it exists throughout the function because it was declared with var.
3. 150 would still be logged cause the last time finalPrice is reassigned is in the last iteration of the for loop, and it is declared earlier with var so it exists in the whole function.
4. This function would return the array [50, 100, 200]. There is a for loop within the function that applies the discount to each price in the array passed in and adds it to the array to be returned. The array and the variables declared in the function are declared with the var keyword so they exist throughout the function.
5. This code would cause an error because the variable i is declared in the above for loop with let, meaning that its scope is limited to the for loop. Because here the code tried to access i outside the for loop, it does not exist there and causes an error.
6. 
