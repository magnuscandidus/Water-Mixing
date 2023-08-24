# Water-Mixing
# cook your dish here
for i in range(int(input())):
    a,b,x,y = map(int, input().split())
    ans='NO'
    if a>=b and y>=a-b:
        ans='YES'
    elif a<=b and x>=b-a:
        ans='YES'
    print(ans)
