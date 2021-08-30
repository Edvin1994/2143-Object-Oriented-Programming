## Program 2 - MyVector Class 2
#### Due: 09-22-2021 (Wednesday @ 12:00 p.m.)

# Not Done !!

## Overview

Using code from [repl.it](https://replit.com/@rugbyprof/StackQueueDay2-3#main.cpp) create a more robust `MyVector` class that includes some added functionality.


## Requirements
- Overload `[]` so that your `MyVector` can be treated as an array. 
- Overload `<<` (ostream) so that if your vector were used in a `cout` statement it would print the entire vector without a newline.
- Overload `+` (addition) so that if your vector were used in an arithmetic operation, it would add two vectors together. 
- Overload `-` (substraction) so that if your vector were used in an arithmetic operation, it would subtract two vectors. 
- Overload `*` (multiplication) so that if your vector were used in an arithmetic operation, it would multiply two vectors. 
- Overload `/` (division) so that if your vector were used in an arithmetic operation, it would divide two vectors. 
- Overload `==` (equality) so that if your vector were used in an arithmetic operation, it would test for equality. 
- Overload `=` (assignment) so that you can assign another vector and take on its values.
- Overlad `push_back` to accept an array of values which will be appended to the existing vector.


## Testing your code

Given:

```cpp

Vector<int> v1;
Vector<int> v2;

v1.push_back(8);
// v1 contains: [8]

v2.push_back(10);
v2.push_back(20);
v2.push_back(30);
// v2 contains: [10,20,30]

// Declare some int array
int A[] = {1,2,3,4,5}


v1.push_back(A,5);
// v1 contains: [8,1,2,3,4,5]

v1 = v1 + v2;
// v1 contains: [18,21,32,3,4,5]

cout<<v1<<endl;
// would print: [18,21,32,3,4,5] to standard out.

cout<<v1[2]<<endl;
// would print: 32 to standard out.


v2 = v2 * 3;
// v2 contains: [30,60,90]

v2 = v2 * v1;
// v2 contains: [540,1260,2880]

v2[2] = 100;
// v2 contains: [540,1260,100]

// What about strings??

```


