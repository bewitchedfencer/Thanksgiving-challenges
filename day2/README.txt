Day 2

Matrix addition

In Mathematics, a matrix is a two dimension set of numbers composed of rows and columns.
ex.
	[	1	2	3		this is a 3x3 matrix
		2	3	4
		3	4	5	]

Matrix addition is a fairly straightforward operation.  Simply, each item in one matrix is added to the corresponding item in the second matrix.
ex.
	[	1	2	3				[	1	2	3			[	2	4	6	
		2	3	4		+			1	2	3		=		3	5	7	
		3	4	5	]				1	2	3	]			4	6	8	]

In javaScript, we can mimic a matrix by using a two-dimensional array
ex.
	var myArray = [			//this is just an array of arrays
		[2,4,6],
		[3,5,7],
		[4,6,8]
	];
	console.log( myArray[1][2] );	//will print 7



Write a function that takes two 'matricies' as aruments and returns a matrix as a result.
ex.
	var matrix1 = [[1,2],[3,4]];		//the function should be able to handle any size matrix
	var matrix2 = [[3,3],[4,3]];		//although, for addition to work both matricies must be the same size.
	addMatrix(matrix1, matrix2);		//	[ [4,5], [7,7] ]

Bonus:
	As mentioned in the comment above, only matricies of the exact same dimensions can be added(or subtracted).
	Create a second function for subtracting matricies, and add validation to both functions so that they return undefined, false, or an error message upon addition.
ex.
	var matrix1 = [[2,2]];				// 1x2 matrix
	var matrix2 = [[4],[5]];			// 2x1 matrix
	addMatrix(matrix1, matrix2);		// undefined


Learn Something:
	Why might a programmer need to use matricies?  Find some use-cases for matrix addition.