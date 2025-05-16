#write a program to print reverse of n natural of n natual number n=5
#output: 5 4 3 2 1
n= int(input("enter the value of n:"))
i=n
while i>=1:            #5>=1  4>=1  3>=1  2>=1  1>=1  0>=1 f 
    print(i, end=' ') #5     4     3    2      1
    i-=1              #i=4   3      2   1      0
