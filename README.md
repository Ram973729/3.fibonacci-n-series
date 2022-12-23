# 3.fibonacci-n-series
n=int(input('Enter any number:'))
a=0
b=1
while n!=0:
    c=b
    b=a+b
    a=c
    print(b)
    n=n-1
