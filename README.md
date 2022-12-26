# 3.fibonacci-n-series
n=int(input('Enter any number:'))
a=0
b=1
while n!=0:
    print(a)
    c=b
    b=a+b
    a=c
    n=n-1
