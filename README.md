# whileloop
Today i learn about While loop .
I work on two partten porblems.
first one is :
row=1
while row<=4:
    col=1
    while row>=col:
        print("*",end=" ")
        col+=1
    print()
    row+=1
the output for this promblem is
*
* *
* * * 
* * * *

and secound pattern is:
row=1
while row <4:
    col=4-row
    while col > 0:
        print("*",end = " ")
        col-=1
    print()
    row+=1
the secound pattern is :
* * *
* *
* 
