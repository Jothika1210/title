
n=int(input ("enter the limit less than 99999999999"))
small=99999999999
for i in range(1,n+1):
    print("enter",i,end='')
    a=int(input("th number:"))
    if a<small:
        small=a
print("smallest no. is:",small)


OUTPUT
enter the limit less than 99999999999 6
enter 1th number:56
enter 2th number:74
enter 3th number:37
enter 4th number:21
enter 5th number:90
enter 6th number:67
smallest no. is: 21

