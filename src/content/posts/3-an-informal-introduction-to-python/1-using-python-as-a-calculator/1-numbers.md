Title: Numbers
Authors: 
Categories: python
Date: 2018-01-05 16:50:27
ID: 3.1.1
Modified: 2018-01-05 16:50:27
Path: An Informal Introduction to Python/Using Python as a Calculator
Slug: numbers
Tags: introduction

<a id="numbers" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

# Numbers

The interpreter acts as a simple calculator: you can type an expression at it and it will write the value. Expression syntax is straightforward: the operators  ```+``` ,  ```-``` ,  ```*```  and  ```/```  work just like in most other languages (for example, Pascal or C); parentheses ( ```()``` ) can be used for grouping. For example:

```python
 >>> 2 + 2 
 4 
 >>> 50 - 5*6 
 20 
 >>> (50 - 5*6) / 4 
 5.0 
 >>> 8 / 5  # division always returns a floating point number 
 1.6
```

The integer numbers (e.g.  ```2``` ,  ```4``` ,  ```20``` ) have type  ```int``` , the ones with a fractional part (e.g.  ```5.0``` ,  ```1.6``` ) have type  ```float``` . We will see more about numeric types later in the tutorial.

Division ( ```/``` ) always returns a  ```float``` . To do floor division and get an integer result (discarding any fractional result) you can use the  ```//```  operator; to calculate the remainder you can use  ```%``` :

```python
 >>> 17 / 3  # classic division returns a float 
 5.666666666666667 
 >>>
>>> 17 // 3  # floor division discards the fractional part 
 5 
 >>> 17 % 3  # the % operator returns the remainder of the division 
 2 
 >>> 5 * 3 + 2  # result * divisor + remainder 
 17
```

With Python, it is possible to use the  ```**```  operator to calculate powers:

```python
 >>> 5 ** 2  # 5 squared 
 25 
 >>> 2 ** 7  # 2 to the power of 7 
 128
```

etc.