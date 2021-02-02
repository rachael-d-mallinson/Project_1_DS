# Project_1_DS

Polynomial Calculator
January 2021 - Intro to Data Structures with Java
Project 1B

TEAM SIX
 - Rachael Mallinson
 - Sofia Nikas
 - Aleksis Martin

Language: Java in eclipse

Design Explanation

First we created a Term class defined by 2 integers (the coefficient and the exponent). Then, we split the polynomial entered by the user - isolating each string separated by the “+” sign. By doing this, we were able to identify the coefficient and exponent in each string and create Terms. The role of our first ArrayList is to hold those Terms. 
Then we sorted the ArrayList in decreasing order by exponent, and combined any coefficients with the same exponent.  We accomplished this by iterating through the list and comparing each term’s exponent to every other term, to see if they needed to be combined. 
The last step was to output the resulting  polynomial to the console as a string in a user-friendly fashion.
For additional usability we added menu options, giving the user the opportunity to continue adding polynomials or to exit the program.


How to use the Polynomial Calculator:
1. Open and Run the Main program.
2. Choose from the numbered list, and enter that number.
3. When prompted, enter your two polynomials that you want added together.
   The added and simplified Polynomial will show in the console.
4. Start over if you wish.
