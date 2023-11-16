# References
what is a reference in c++? a reference is like a dereferenced pointer, it could be viewed as a constant pointer to a variable
where each time we use it is dereferenced. We must bound it to a variable during initialization and cannot reassign it. If we print
the address of a reference it returns the same address of the variable who is bounded.

int x = 3;
int* ptrx = &x; //pointer to x
int& rx = x; //reference to x
rx = 3; //equivalent to *ptrx


&x and &rx are the same while a pointer has its own address, can be rebound etc.