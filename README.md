# assignment-2-19-02-22-
prime number
Q=int(input())
While(Q>0):
X,y=[int(x) for x in input (). split ()]
Sum=0
for num in range (X+1,Y): #num=1 num=2 num=3 num=4
C=0
for var in range (1,1+num): #(1,1) (1,2) (1,2) (1,4)
If (num%var==0):
C+=1
If (c==2):
Sum=sum+1
Q-=1
Print(sum)

output:
enter number:25
1229
