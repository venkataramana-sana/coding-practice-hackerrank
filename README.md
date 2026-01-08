C0DE-1
 a = int(input())
    b = int(input())
    print(a//b)  # it is used for float value can round of to inter value
    print(a/b)
    
CODE -2 ( SQUARE )
a = int(input())
for i in range(a):
    print(i*i)
    
CODE-3
TASK:Chef is playing Ludo. According to the rules of Ludo, a player can enter a new token into the play only when he rolls a 6 on the die.
In the current turn, Chef rolled the number X
X on the die. Determine if Chef can enter a new token into the play in the current turn or not.

ANSWER:
t = int (input())
for _ in range(t):
    n=int(input())
    if n>=6 :
        print("YES")
    else:
        print("No")
CODE -4
Task:
Given an integer,N , perform the following conditional actions:
If N is odd, print Weird
If N is even and in the inclusive range of 2 to 5, print Not Weird
If N is even and in the inclusive range of 6 to20 , print Weird
If N is even and greater than 20 , print Not Weird

ANSWER:
 n = int(input().strip())
    if n%2 !=0:
        print("Weird")
    elif n%2==0 and 2<n<5:
        print("Not Weird")
    elif n%2==0 and 6<n<=20:
        print("Weird")
    elif n%2 ==0 and n>20:
        print("Not Weird")
