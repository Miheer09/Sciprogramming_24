# Practical07
This is practical 7 in this we are excecuting two codes.In the first code we find the estimates value of 'e'and the difference between the estimate value of 'e' and the true value of e.
* With the increasing polynomial order increases the difference getting more greater upto a certain number. 
* As the order increases the factorial value aslo increases exponentially because of which the value of e gets extremely small. 
## Compile:

## 1. Difference in estimate 'e' value and true value:

bash
gcc -o facte facte.c -lm


# Execute:

bash
./facte

Please enter the required polynomial order 
1
e is estimated as 2.0000000000, with difference -7.182818e-01

./facte 
Please enter the required polynomial order 
10
e is estimated as 2.7182818011, with difference -2.731266e-08

./facte 
Please enter the required polynomial order 
12
e is estimated as 2.7182818283, with difference -1.728764e-10

./facte 
Please enter the required polynomial order 
13
e is estimated as 2.7182818288, with difference 3.447078e-10

./facte
Please enter the required polynomial order 
14
e is estimated as 2.7182818296, with difference 1.126602e-09

./facte 
Please enter the required polynomial order 
15
e is estimated as 2.7182818301, with difference 1.625527e-09

*In the next code we have excuted dynamic memory allocation using poinsters along with arry manipulation and pointer handling and freeing the allocated memory.
## Compile:

## 1. Difference in estimate 'e' value and true value:

bash
gcc -o facte facte.c -lm


# Execute:

bash
./facte

Please enter the required polynomial order 
1
e is estimated as 2.0000000000, with difference -7.182818e-01

./facte 
Please enter the required polynomial order 
10
e is estimated as 2.7182818011, with difference -2.731266e-08

./facte 
Please enter the required polynomial order 
12
e is estimated as 2.7182818283, with difference -1.728764e-10

./facte 
Please enter the required polynomial order 
13
e is estimated as 2.7182818288, with difference 3.447078e-10

./facte
Please enter the required polynomial order 
14
e is estimated as 2.7182818296, with difference 1.126602e-09

./facte 
Please enter the required polynomial order 
15
e is estimated as 2.7182818301, with difference 1.625527e-09
