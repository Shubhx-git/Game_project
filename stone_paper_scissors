import random
'''1 for stone
-1 for paper
0 for scissors'''

computer= random.choice([1,-1,0])
youstr= input("enter your choice: ")
youDict= {"stone":1, "paper":-1, "scissors":0}
reverseDict= {1:"stone", -1:"paper", 0:"scissors"}

you= youDict[youstr]
print(f"you choose: {reverseDict[you]}\n computer choose: {reverseDict[computer]}")

def main():
 if(computer==1 and you==-1):
    print("you win!")
 elif(computer==1 and you==0):
    print("you lose!")
 elif(computer==-1 and you==1):
    print("you lose!")
 elif(computer==-1 and you==0):
    print("you win!")
 elif(computer==0 and you==-1):
    print("you lose!")
 elif(computer==0 and you==1):
    print("you win!")
 else:
    print("its Draw!")

main()