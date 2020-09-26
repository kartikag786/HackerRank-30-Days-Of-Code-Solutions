fine=0
a=list(map(int,input().split()))
e=list(map(int,input().split()))
if e[2]<a[2]:
    fine=10000
elif(e[2]==a[2]):
    if e[1]<a[1]:
        fine=abs((a[1]-e[1])*500)
    elif e[1]==a[1] and e[0]<a[0]:
        fine=abs((a[0]-e[0])*15)

print(fine)