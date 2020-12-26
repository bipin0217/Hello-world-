# Hello-world Guess my name here.
I am new to use github.So here u have to guess my name .

a='Bipin'
print("YOU HAVE TO GUESS MY NAME IN SEVERAL ATTEMPT'S YOU WANT")
n=int(input("Enter no. of attempts you want : \n"))
for i in range(1,n+1):
    c=input("Guess my name : \n")
    if a==c:
        print("you have gussed correct name in ",i-1,"attempt")
    else :
        print("you have gussed wrong ",n-i,"chances remaining")
