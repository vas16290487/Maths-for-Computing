# Solutions

### Part 1
  a)
  
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
      prev_q = q
      prev_r = r
      r = q - ((q // r) * r)
      q = prev_r
    
    print("Result:", prev_r)
  ```
  
### Part 2
  a) This task asks for the sum of all numbers in a n<sup>th</sup> term range of numbers.
    n<sup>th</sup> term: 
