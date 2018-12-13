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
   = 1032  
