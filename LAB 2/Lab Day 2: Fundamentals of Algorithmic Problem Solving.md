**2.1 Aim of the program:** Write a program in C to convert the first ‘n’ decimal numbers of a disc file to binary using recursion. Store the binary value in a separate disc file.  
_Note:_ Read the value of ‘n’, source file name and destination file name from command line arguments. Display the decimal numbers and their equivalent binary numbers from the output file.  
Give the contents of the input disc file "inDec.dat" as 30 75 2564 ...  
Contents of the output disc file "outBin.dat" as
- The binary equivalent of 30 is 0000000000011110
- The binary equivalent of 75 is 0000000001001011
- The binary equivalent of 2564 is 0000101000000100

_Terminal Input:_
$gcc lab2q1.c -o lab2q1
$./lab2q1 150 inDec.dat outBin.dat

_Output:_ Content of the first 'n' decimal and their binary equivalents
