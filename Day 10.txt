n = int(input())
bno = bin(n).replace("0b", "") #in built function
c = list(bno)
count = 0
temp = 0
for i in c:
    if(i == '1' ):
        temp +=1
        if temp > count:
            count = temp
    else:
        temp = 0
        
print(count)
