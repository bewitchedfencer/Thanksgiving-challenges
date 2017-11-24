Day 1

Factorial

The Factorial operator (!) takes a positive whole number and multiplies it by each positive whole number that is smaller thab the original number.
ex. 
	3! = 3*2*1 = 6
	5! = 5*4*3*2*1 = 120



Write a function called 'factorial' that takes a single argument and returns the factorial of that number.
ex.
	factorial(3) 		// when typed into the console, it should print 6
	factorial(5) 		// 120

Bonus:
	Factorial has some exceptions.  You cannot use factorial on negative or non-whole numbers.  Additionally, zero factorial equals one.
	ex.
		factorial(3.1) 	// false or undefined or error message
		factorial(-2) 	// false or undefined or error message
		factorial(0) 	// 1

	Add logic to your function to handle the above exceptions.  For the unusable value, you may decide what to have your function return.

Learn Something:
	Find some use-cases for a factorial function.