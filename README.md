''' calculate the money ,which is deposited in piggy bank with different denomination use :1,2,5,10.
input :10=5 ,5=5,2=10,10=5
output:100'''

ten=int(input("enter 10 denominations"))
five=int(input("enter 5 denominations"))
two=int(input("enter 2 denominations"))
one=int(input("enter 1 denominations"))
total=(10*ten)+(5*five)+(2*two)+(1*one)
print("the total amount in piggy bank",total)
