n=int(input())
d={}
for i in range(n):
    ti=tuple(input().split())
    d[ti[0]]=ti[1]
nm=[]
while(True):
    try:
        search = input()
        if search in d:
            print('{}={}'.format(search, d[search]))
        else:
            print('Not found')
    except EOFError:
        break
