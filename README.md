n=int(input("Enter a number:"))
k=30
for i in range(1,k+1):
    s=str(n)[::-1]
    n = n + int(s)
    if (str(n)==str(n)[::-1]):
        print(i,n)
        break   
else:
    print("[-1,-1]")
