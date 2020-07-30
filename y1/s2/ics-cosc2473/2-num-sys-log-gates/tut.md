### ICSTUT2. Introduction and Number Systems  

Number conversions:
Division method:

Action:  Remainder:
29/5=5   4  
5/5=1    0  
1/5=0    1  

So 29 base 10 is 104 base 5


Powers method:
29 base 10 is made of 25 (5^2) zero 5's and 4 1's.  
ie. 4, 0, 1 in base 5.  

Q1. What is the largest number you can get with:  

4 bits = 1111 = 15 (16 states, ie. 0-15) 
8 bits = .... = 255 (256 states)  
16 bits = ... = 65,535 (65,536 states)  

(2^n-1 max number, 2^n stages)  

####Number System Conversion:  

Q2. Decimal to binary, octal, hexadecimal:  
1. - 117 base 10 - 1110101 base 2  
  - 165 base 8  
  - 75 base 16 

117/ 2 = 58 r 1  
58 / 2 = 29 r 0  
29 / 2 = 14 r 1  
14 / 2 = 7  r 0  
7  / 2 = 3  r 1  
3  / 2 = 1  r 1  
1  / 2 = 0  r 1  

reading up we get 1110101 in binary.  


2. - 127 base 10 - 1111111 base 2  
  - 177  
  - 7F  

3. - 128 base 10 - 10000000 base 2 
  - 200 base 8  
  - 80 base 16  

4. - 255 base 10 - 11111111 base 2  
  - 377 base 8
  - FF base 16  

Q3. Other bases to decimal:  
1. - 1101 base 2 - to decimal:  

1 * 2^0 = 1  
0 * 2^1 = 0  
1 * 2^2 = 4  
1 * 2^3 = 8  

1 + 0 + 4 + 8 = 13 base 10  

2. - 7014 base 8 to decimal:  

4 * 8^0 = 4  
1 * 8^1 = 8  
0 * 8^2 = 0  
7 * 8^3 = 3584  

4 + 8 + 3584 = 3596 base 10  

Q4. Other base system:  
1. Convert 217 base 10 to base 7:  
217/7 = 31 r 0  
31/7  = 4  r 3  
4/7   = 0  r 4  

430 in base 7  

2. Convert 1101 base 2 to base 5:

we either convert to decimal as above and use the divide method to convert to base 5. 
or...

we can  construct numbers in its base eg. 1101 in binary  
1  
1 * 2 = 10  (2)  
10+ 1 = 11  (3)  
11 * 2 = 110  (6)  
100+0 = 110
100 * 2 = 1100 (12)  
1000 + 1 = 1101 (13)  

if we construct into a different base, we multiply by our old base but all numbers are represented in the new base:  

1
1 * 2  = 2  (mkae sure to multiply in the target base!)
2 + 1 = 3  
3 * 2 = 11 (6 in base 10)  
11 + 0 = 11  
11 * 2 = 22  
22 + 1 = 23 in base 5  
or 13 in decimal.  

3. Convert 7014 base 8 to base 9:  

7  
7 * 8 = 62  (56 in base 10, 56/9 = 6 r 2, 6/9 = 0 r 6, so 62 in base 9, or 6 * 9 = 54 + 2)  
62 + 0 = 62  
62 * 8 = 547 (448 in base 10)  
547 + 1 = 548  
612 * 8 = 4761 (3592 in base 10)   
4761 + 4 = 4765  (=3596 on base 10)
