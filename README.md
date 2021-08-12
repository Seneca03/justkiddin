#fibbonacci genarator

print("fibbonacci series")
count=int(input('enter the number of terms '))
i=1
a=0
sum=0
for j in range(count):
    sum=a+i
    i=a
    a=sum
    print(sum,end="   ")
print()
print('bye')
