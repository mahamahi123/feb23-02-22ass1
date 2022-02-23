# feb23-02-22ass1
Max and min value
#write a program to print max and min elements from the list.
l=[]
n=int(input())
for i in range(n):
    x=int(input())
    l.append(x)
min=l[0]
max=l[0]
for i in range(1,n):
    if l[i]<min:
        min=l[i]
    for i in range(1,n):
        if l[i]>max:
            max=l[i]
print('min',min)
print('max',max)
