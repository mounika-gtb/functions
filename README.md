# functions
def fun(n):
   string=0
   for i in range(1,n+1):
      if 1<=n and n<=150:
         string=string*10+i
   return string
n=int(input())
print(fun(n))
