# Multiplication-Table
Here user will enter a value n and the application will display the mathematical mutiplication table till given value n.

class multiplyTable():
    description="Generates multiplication table"
    def table(n):
        for i in range(2,n+1): # For every number between 2 and n
            print("\nmultiplication table for %d\n"%i)
            for j in range(n+1):
                print("%d x %d = %d"%(i,j,i*j))

val=int(input("Enter the value For the table :"))
print("|  multiplication Table  |")

multiplyTable.table(val)
