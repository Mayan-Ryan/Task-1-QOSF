# Task-1-QOSF

### Problem Statement

To find the largest number

You have two integers, either positive or negative, and the challenge is to generate a quantum algorithm that returns which is the larger number. Consider an appropriate number of qubits and explain why your proposal is valid for all kinds of numbers in case 


def find_the_largest_number (int:number_1, int ,number_2):

   number_1 : integer value that is the first parameter to the function,
   
   number_2 : integer value that is the second parameter to the function.
   
   Return the largest number between number_1 and number_2


Example:

A = find_the_largest_number(5,-6)

print(A)

“5”

### Implementation

To solve this problem, I made use of Qiskit. I also used IBM quantum composer to visualize the circuit. The logic of the program is basically to create a combinational  circuit that first checks if a number is positive or negative, assigns qubit to store the sign magnitude and the absolute value of the bit number and performs compare operation accordingly while retaining the sign of the number.
