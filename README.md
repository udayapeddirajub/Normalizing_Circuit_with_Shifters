# Normalizing_Circuit_with_Shifters
Input and output data is taken as 8-bit reg data type, as per the design statement we have to normalize the input 
number by shifting the input data to the left till the leading bit(MSB) becomes 1. The number of shifts required can 
be calculated in two ways: the shifter using the RTL operator(shuffled wire) and the barrel shifter, the priority encoder used as the 
control block in both of the designs.

The attached zip file contains all the required design and test scripts.
