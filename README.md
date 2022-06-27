# 90-days

Day:1 Recursion

1. Calculate the fibonacci series using recursion:

def fibo(n):
    assert n>=0 and int(n)==n," Fibonnaci number cannot be negative and non integer"
    if n in [0,1]:
        return n
    else:
        return fibo(n-1)+fibo(n-2)
    
fibo(10)

2. How to find the sum of digits of positive integer using recursion.

def sumofdigits(n):
    assert int(n)==n and n>0, "Number should be interger and postive"
    if n>10:
        return int(n%10)+sumofdigits(int(n/10))
    else:
        return n


sumofdigits(123)


3.  How to calculate power of any number using recursion.

