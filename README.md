# Bash-Matrix-Manipulation
Bash Matrix Manipulation

Run in bash:
matrix OPERATION [ARGUMENT]:
Where Operation can be dims, transpose, mean, add, or multiply
Matrix if a text file of an MxN matrix of numbers. Each number is separated by a tab
EX: cat -A matrix1
8^I5^I6$
3^I2^I2$
1^I6^I7$
5^I0^I7$
2^I2^I4$

#Note: ^I represents a tab and $ represents a newline character

Various Options:
matrix dims [MATRIX]
dims prints the dimensions of the matrix as the number of rows, then the number of columns.

matrix transpose [MATRIX]
transpose reflects the elements of the matrix along the main diagonal. 
Thus, an MxN matrix will become an NxM matrix and the values along the main diagonal will remain unchanged.

matrix mean [MATRIX]
mean should take an MxN matrix and return an 1xN row vector, where the first element is the mean of column one, the second element is the mean of column two, and so on.

matrix add MATRIX_LEFT MATRIX_RIGHT
add should take two MxN matrices and add them together element-wise to produce an MxN matrix. 
add should return an error if the matrices do not have the same dimensions.


matrix multiply MATRIX_LEFT MATRIX_RIGHT
multiply should take an MxN and NxP matrix and produce an MxP matrix. Note that, unlike addition, matrix multiplication is not commutative. 
