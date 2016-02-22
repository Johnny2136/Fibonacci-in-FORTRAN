# Fibonacci-in-FORTRAN
Continuation of Fibonacci
```fortran
PROGRAM FIBONACCI 
INTEGER FIB,F1,F2 
FIB = 0 
FIBn1 = 0 
FIBn2 = 1
DO WHILE (FIB .LT. 500) 
PRINT *, FIB 
FIB = FIBn1 + FIBn2 
FIBn1 = FIBn2 
FIBn2 = FIB 
END DO 
END 
```
