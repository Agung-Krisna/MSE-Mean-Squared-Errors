# MSE-Mean-Squared-Errors
This is a program to automate the process of finding MSE

### Algorithm
***view this on the raw version, so that you don't get a headache***<br>
//there’s a lot of loops, you don’t need to implement all of the loops here, but I used it //in order to make different functions

let list A, B, C
let sum = 0
input list into A and B
let max = length of A or B
//inputting A
for x in range max
	input list A
//inputting B
for x in range max
	input list B
for x in range max:
	C[x] = list A[x] – list B[x]
for x in range max:
	C [x] = C[x] ** 2
for x in range max:
	sum = sum + C[x]
mean = sum / max
DISPLAY mean
