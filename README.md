# DIY
s=input("Enter a word:")
print("\n")
def display(w):
    if w=='a' or w=='A':
        for i in range(1,6):
            for j in range(1,10):
                if i+j==6 or j-i==4 or (i==3 and j>3 and j<7):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='b' or w=='B':
        for i in range(1,8):
            for j in range(1,9):
                if j==1 or ((i==1 or i==4 or i==7) and j<8) or (j==8 and (i!=1 and i!=4 and i!=7)):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='c' or w=='C':
        for i in range(1,8):
            for j in range(1,9):
                if ((i==1 or i==7) and j!=1) or (j==1 and (i!=1 and i!=7)):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='d' or w=='D':
        for i in range(1,8):
            for j in range(1,10):
                if j==1 or ((i==1 or i==7) and j<8) or (j==8 and (i==2 or i==6)) or (j==9 and (i>2 and i<6)):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='e' or w=='E':
        for i in range(1,8):
            for j in range(1,9):
                if j==1 or i==1 or i==7 or i==4:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='f' or w=='F':
        for i in range(1,8):
            for j in range(1,9):
                if j==1 or i==1 or i==4:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='g' or w=='G':
        for i in range(1,8):
            for j in range(1,10):
                if ((i==1 or i==7) and j!=1 and j!=9) or (j==1 and (i!=1 and i!=7)) or (j==9 and (i>3 and i<7)) or (i==4 and (j>5 and j<10)):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='h' or w=='H':
        for i in range(1,8):
            for j in range(1,10):
                if j==1 or j==9 or i==4:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='i' or w=='I':
        for i in range(1,8):
            for j in range(1,9):
                if ((i==1 or i==7) and j>1) or j==5:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='j' or w=='J':
        for i in range(1,8):
            for j in range(1,10):
                if i==1 or (j==5 and i!=7) or (i==7 and j>1 and j<5) or (j==1 and i>4 and i<7):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='k' or w=='K':
        for i in range(1,9):
            for j in range(1,8):
                if j==1 or i+j==6 or i-j==2:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='l' or w=='L':
        for i in range(1,8):
            for j in range(1,8):
                if j==1 or i==7:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='m' or w=='M':
        for i in range(1,8):
            for j in range(1,8):
                if j==1 or j==7 or (i==j and j<5) or (i+j==8 and (j>4 and j<7)):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='n' or w=='N':
        for i in range(1,8):
            for j in range(1,8):
                if j==1 or j==7 or i==j:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='o' or w=='O':
        for i in range(1,8):
            for j in range(1,8):
                if ((j==1 or j==7) and (i>1 and i<7)) or ((i==1 or i==7) and (j>1 and j<7)):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='p' or w=='P':
        for i in range(1,8):
            for j in range(1,8):
                if j==1 or ((i==1 or i==4) and j<7) or (j==7 and (i>1 and i<4)):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='q' or w=='Q':
        for i in range(1,9):
            for j in range(1,9):
                if ((j==1 or j==7) and (i>1 and i<7)) or ((i==1 or i==7) and (j>1 and j<7)) or (i==j and i>3):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='r' or w=='R':
        for i in range(1,9):
            for j in range(1,8):
                if j==1 or ((i==1 or i==4) and j<7) or (j==7 and (i>1 and i<4)) or i-j==2:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='s' or w=='S':
        for i in range(1,8):
            for j in range(1,8):
                if (j==1 and i<4 and i>1) or ((i==1 or i==4 or i==7) and j>1 and j<7) or (j==7 and i>4 and i<7):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='t' or w=='T':
        for i in range(1,8):
            for j in range(1,11):
                if j==5 or i==1:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='u' or w=='U':
        for i in range(1,8):
            for j in range(1,9):
                if ((j==1 or j==8) and i<7) or (i==7 and j>1 and j<8):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='v' or w=='V':
        for i in range(1,7):
            for j in range(1,12):
                if i==j or j+i==12:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='w' or w=='W':
        for i in range(1,7):
            for j in range(1,16):
                if i==j or (j+i==12 and i>3) or (j-i==4 and i>3) or i+j==16:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='x' or w=='X':
        for i in range(1,8):
            for j in range(1,8):
                if i==j or i+j==8:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='y' or w=='Y':
        for i in range(1,8):
            for j in range(1,8):
                if (i==j and i<5) or (i+j==8 and i<5) or (j==4 and i>4):
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w=='z' or w=='Z':
        for i in range(1,8):
            for j in range(1,8):
                if i==1 or i==7 or i+j==8:
                    print(end='*')
                else:
                    print(end=' ')
            print()
        print('\n\n')
    if w==' ':
        print("\n\n\n\n\n\n")
for i in s:
    display(i)
