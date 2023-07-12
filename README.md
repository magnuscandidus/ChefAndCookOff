# ChefAndCookOff
# cook your dish here
t=int(input())
while t:
    a=list(map(int,input().split()))
    c=a.count(1)
    if(c==0):
        print("Beginner")
    elif(c==1):
        print("Junior Developer")
    elif(c==2):
        print("Middle Developer")
    elif(c==3):
        print("Senior Developer")
    elif(c==4):
        print("Hacker")
    else:
        print("Jeff Dean")
    t-=1
