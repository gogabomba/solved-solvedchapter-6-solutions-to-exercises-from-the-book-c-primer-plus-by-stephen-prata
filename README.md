Download Link: https://assignmentchef.com/product/solved-solvedchapter-6-solutions-to-exercises-from-the-book-c-primer-plus-by-stephen-prata
<br>
Exercise 1:

Write a program that creates an array with 26 elements and stores the 26 lowercase etters in it. Also have it show the array contents.

Exercise 2:

Use nested loops to produce the following pattern:$$$$$$$$$$$$$$$

Exercise 3:

Use nested loops to produce the following pattern:FFEFEDFEDCFEDCBFEDCBA

Exercise 4:

Use nested loops to produce the following pattern:

ABCDEFGHIJKLMNOPQRSTU

Exercise 5:

Have a program request the user to enter an uppercase letter. Use nested loopsto produce a pyramid pattern like this:AABAABCBAABCDCBAABCDEDCBAThe pattern should extend to the character entered. For example, the precedingpattern would result from an input value of E.

Exercise 6:Write a program that prints a table with each line giving an integer, its square, and its cube. Ask the user to input the lower and upper limits for the table. Use a for loop

Exercise 7:

Write a program that reads a single word into a character array and then printsthe word backward. Hint: Use strlen() (Chapter 4) to compute the index of thelast character in the array

Exercise 8:

Write a program that requests two floating-point numbers and prints the value oftheir difference divided by their product. Have the program loop through pairsof input values until the user enters nonnumeric input.

Exercise 9:

Modify exercise 8 so that it uses a function to return the value of the calculation.

Exercise 10:

Write a program that requests lower and upper integer limits, calculates the

sum of all the integer squares from the square of the lower limit to the

square of the upper limit, and displays the answer. The program should then

continue to prompt for limits and display answers until the user enters an

upper limit that is equal to or less than the lower limit. A sample run should

look something like this:

Enter lower and upper integer limits: 5 9

The sums of the squares from 25 to 81 is 255

Enter next set of limits: 3 25

The sums of the squares from 9 to 625 is 5520

Enter next set of limits: 5 5

Done

Exercise 11:

Write a program that reads eight integers into an array and then prints them in reverse order.

Exercise 12:Consider these two infinite series:

1.0 + 1.0/2.0 + 1.0/3.0 + 1.0/4.0 + …

1.0 – 1.0/2.0 + 1.0/3.0 – 1.0/4.0 + …

Write a program that evaluates running totals of these two series up to some

limit of number of terms. Hint: –1 times itself an odd number of times is –1,

and –1 times itself an even number of times is 1. Have the user enter the limit

interactively; let a zero or negative value terminate input. Look at the running

totals after 100 terms, 1000 terms, 10,000 terms. Does either series appear to

be converging to some value?

Exercise 13:Write a program that creates an eight-element array of ints and sets the elements to the first eight powers of 2 and then prints the values. Use a for loop to set the values, and, for variety, use a do while loop to display the values.

Exercise 14:

Write a program that creates two eight-element arrays of doubles and uses aloop to let the user enter values for the eight elements of the first array.Have the program set the elements of the second array to the cumulative totalsof the elements of the first array. For example, the fourth element of thesecond array should equal the sum of the first four elements of the firstarray, and the fifth element of the second array should equal the sum of the first five elements of the first array. (It’s possible to do this with nested loops, but by using the fact that the fifth element of the second array equals the fourth element of the second array plus the fifth element of the first array, you can avoid nesting and just use a single loop for this task.)Finally, use loops to display the contents of the two arrays, with the first array displayed on one line and with each element of the second array displayedbelow the corresponding element of the first array.

Exercise 15:

Write a program that reads in a line of input and then prints the line in reverse order. You can store the input in an array of char; assume that the line is no longer than 255 characters. Recall that you can use scanf() with the %c specifier to read a character at a time from input and that the newline character (
) is generated when you press the Enter key

Exercise 16:Daphne invests $100 at 10% simple interest. (That is, every year, theinvestment earns an interest equal to 10% of the original investment.) Deirdreinvests $100 at 5% interest compounded annually. (That is, interest is 5% of the current balance, including previous addition of interest.) Write a program that finds how many years it takes for the value of Deirdre’s investment to exceed the value of Daphne’s investment. Also show the two values at that time.

Exercise 17:Chuckie Lucky won a million dollars (after taxes), which he places in an account that earns 8% a year. On the last day of each year, Chuckie withdraws $100,000. Write a program that finds out how many years it takes for Chuckie to empty his account.

Exercise 18:

Professor Rabnud joined a social media group. Initially he had five friends. He noticed that his friend count grew in the following fashion. The first week one friend dropped out and the remaining number of friends doubled. The second week two friends dropped out and the remaining number of friends doubled. In general, in the Nth week, N friends dropped out and the remaining number doubled. Write a program that computes and displays the number of friends each week. The program should continue until the count exceeds Dunbar’s number. Dunbar’s number is a rough estimate of the maximum size of a cohesive social group in which each member knows every other member and how they relate to one another. Its approximate value is 150.