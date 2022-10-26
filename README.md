# Day4-Lab3-Loop

1) Using **range()**, make a range from 45 to 210, using a for loop iterate over the sequence and print the elements. Skip the number 100 and break the loop at 205.

for num in range(45,210):
    if (num == 100):
        continue
    elif (num == 205):
        break
    print(num)

2) Using a **while loop** and **input**, do the following:
- Ask the the user : "what is the product of 7 * 24 ?"
- Check if the answer is right then exit the loop and print "You answered this Question correctly".
- If the answer is wrong, then print "Your Answer is wrong try again.." and show the user the question again.

x= True
while x == True:
    userAnswer = input("what is the product of 7 * 24? ")
    if(userAnswer == '168'):
        break
    else:
        print ("Your Answer is wrong try again.." )
print ("You answered this Question correctly.")
