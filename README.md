# 8.leap-years-upto-given-range
n=int(input('Enter any year:'))
for i in range(1000,n+1):
    if i%4==0 and i%100!=0:
        print(i)
    elif i%400==0:
        print(i)
