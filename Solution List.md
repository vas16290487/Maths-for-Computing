# Solutions

### Part 1
  a) Since the brief asked for an app, here are some links corresponding to this app:
  
  - [source code](https://github.com/vas16290487/Maths-for-Computing/blob/Maths-Changes/A1%20-%20LCM%20Calculator%20Hot%20Dogs.html)
  - [app preview](https://htmlpreview.github.io/?https://github.com/vas16290487/Maths-for-Computing/blob/Maths-Changes/A1%20-%20LCM%20Calculator%20Hot%20Dogs.html)
  
  b) Euclid's algorithm for the numbers 288 and 660:
  <pre>
  660 = 2 * 288 + 84
  288 = 3 *  84 + 36
   84 = 2 *  36 + 12
   36 = 3 *  12 +  0
  </pre>
  
  Here's an example of an algorithm, implemented in Python, that asks for 2 numbers and returns the GCD using Euclid's algorithm:
  ```python
    q = int(input("What is the initial quotient? "))
    r = int(input("What is the initial remainder? "))

    while r != 0:
      prev_r = r
      r = q - ((q // r) * r)
      q = prev_r
    
    print("Result:", prev_r)
  ```
  
### Part 2  
  a) 42 ( 1 + 42 ) / 2 =  
   = 24 x 43 =  
   = 1032p = £10.32  
  
  b) 6 * ( 1 - 1.05 ^ 26 ) / ( 1 - 1.05 ) =  
   = 6 * ( 1 - 1.05 ^ 26 ) / 0.05 =  
   = 306.68 minutes (2dp) =  
   = 18401 seconds (nearest second)
   
### Part 3

Formula for multiplicative inverse operations: a x b MOD c = 1

  I. Solutions for multiplicative inverse modulo 9 for the following numbers:
  
  (a) 1
  
   a  |  b  | Remainder
  --- | --- | :-------:
   1  |  0  |     0
   1  |  1  |     1
  
  Solution: b = 1
  
  (b) 5
  
   a  |  b  | Remainder
  --- | --- | :-------:
   5  |  0  |     0
   5  |  1  |     5
   5  |  2  |     1  
   
   Solution: b = 2
   
  (c) 7
  
   a  |  b  | Remainder
  --- | --- | :-------:
   7  |  0  |     0
   7  |  1  |     7
   7  |  2  |     5
   7  |  3  |     3
   7  |  4  |     1
   
   Solution: b = 4
   
  (d) 16
  
   a  |  b  | Remainder
  --- | --- | :-------:
   16 |  0  |     0
   16 |  1  |     7
   16 |  2  |     5
   16 |  3  |     3
   16 |  4  |     1
  
  Solution: b = 4
  
  II. Proof for no solutions for multiplicative inverse modulo 9 for the following numbers:
  
  (a) 0
  
   a  |  b  | Remainder
  --- | --- | :-------:
   0  |  0  |     0
   0  |  1  |     0
   0  |  2  |     0
   0  |  3  |     0
   0  |  4  |     0
   0  |  5  |     0
   0  |  6  |     0
   0  |  7  |     0
   0  |  8  |     0
  
  Solution: The remainder is always 0; thus, it will never reach 1.
  
  (b) 6
  
   a  |  b  | Remainder
  --- | --- | :-------:
   6  |  0  |     0
   6  |  1  |     6
   6  |  2  |     3
   6  |  3  |     0
   6  |  4  |     6
   6  |  5  |     3
   6  |  6  |     0
   6  |  7  |     6
   6  |  8  |     3
  
  Solution: The remainder is always 0, 6 or 3; thus, it will never reach 1.
  
  (c) 18
  
   a  |  b  | Remainder
  --- | --- | :-------:
   18 |  0  |     0
   18 |  1  |     0
   18 |  2  |     0
   18 |  3  |     0
   18 |  4  |     0
   18 |  5  |     0
   18 |  6  |     0
   18 |  7  |     0
   18 |  8  |     0
  
  Solution: The remainder is always 0; thus, it will never reach 1.
  
  
