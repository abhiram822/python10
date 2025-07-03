# python10
#ARM STRONG NUMBER
num=int(input())
n=len(str(num))
temp=num
sum=0
while temp>0:
    d=temp%10
    sum+=d**n
    temp//=10
print("",sum)
print("",temp)
if sum==num:
    print("arm strong number")
else:
    print("not")


