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
