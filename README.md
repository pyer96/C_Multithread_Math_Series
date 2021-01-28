# C_Multithread_Math_Series
Multithread program to evaluate the summation (x/y)^i for i=0...N

This program evaluates the following math series:
 
              		          ___N
                                \      (x^i)
                                 .     _____
                                /__i=0 (y^i)
 
  	The program is multithread, 2*N threads are created. Each thread computes 
  	a single x^i OR y^i instance.
  	The main thread, then, computes the divisions and the final summation.
