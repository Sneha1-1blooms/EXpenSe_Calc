# EXpenSe_Calc
import random
dict={}
WORDS = ("python", "jumble", "easy", "difficult", "answer",  "xylophone")
print('     Hey, Welcome to expense calculator   ')
print(' Please input the list of items & their cost where you have spend')
c=0
for i in range(10):
    print('Input the name of items')
    a= random.choice(WORDS)
    print(a)
    print('Input its cost')
    b=random.randint(1,100)
    print(b)
    dict[a]=b
    c=b+c
    print('Total expenses as of now ' , str(c))
print('Total items bought : ' , i+1)
print(dict)
