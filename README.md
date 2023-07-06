# MakeABequal
# cook your dish here
for i in range(int(input())):
    a, b = map(int, input().split(" "))
    if a == b:
        print("Yes")
    else:
        # check if the number can be achieved or not 
        min = min(a,b)
        max = max(a,b)        
        while(mini<maxi):
            min *= 2            
        if min == max:
            print("Yes")
        else:
            print("No")
