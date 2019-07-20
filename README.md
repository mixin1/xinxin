# 九九乘法表，python
一
for i in range(1,10,):
    for j in range(1,10):
        if i<j :
            break
        print (i, '*', j, '=', i*j, end='  ')
    print()
    
二
for i in range(1,10,):
    for j in range(1,i+1):
        print (i, '*', j, '=', i*j, end='  ')
    print()
    
