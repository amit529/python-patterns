# python-patterns

                      (r)   (5-r)
               r    stars  spaces
*              1     1       4
**             2     2       3
***            3     3       2
****           4     4       1
*****          5     5       0

program
for r in range(1,6):
    print()
    for c in range(r):
        print("*",end="")
    for c in range(5-r):
        print("",end="")
    


                  (6-r)     (r-1)
               r    stars  spaces
*****          1      5       0
****           2      4       1
***            3      3       2
**             4      2       3
*              5      1       4
program
for r in range(1,6):
    print()
    for c in range(6-r):
        print("*",end="")
    for c in range(r-1):
        print("",end="")

                     (r/r+7) 
               r    stars  
++++++++       1     8
********       2     8
++++++++       3     8
********       4     8

program
for r in range(1,5):
    print()
    if(r%2==0):
       sb="*"
    else:
       sb="+"
    for c in range(r/r+7):
         print(sb,end="")

              r       stars/numbers
1             1          1
22            2          2
333           3          3
4444          4          4
55555         5          5

program
for r in range(1,6):
    print()
    for c in range(r):
        print(r,end="")
    

1
23
456
78910
program
a=1
for r in range(1,5):
    print()
    for c in range(r):
        print(a,end="")
        a=a+1
    



    








