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
x=0
y=0
def sum(x,y):\
    
    assert int(x)==x and int(y)==y,"number cannot be non integer and negative"
    if x<0:
        print("x is negative interger")
    elif y<0:
        print("y is negative interger")
    elif x>0 and y>0:
        return x+y
    
sum(2,-3.5)
    
