# Day4-Lab3-Loop

1) Using **range()**, make a range from 45 to 210, using a for loop iterate over the sequence and print the elements. Skip the number 100 and break the loop at 205.
for i in range(45,211):
    if i ==100:
        continue
        print(i)
    elif i==205:
        print(i)
        break
    print(i)

2) Using a **while loop** and **input**, do the following:
- Ask the the user : "what is the product of 7 * 24 ?"
- Check if the answer is right then exit the loop and print "You answered this Question correctly".
- If the answer is wrong, then print "Your Answer is wrong try again.." and show the user the question again.

while True:
    x = int(input('What is the product of 7*24 '))
    if x == 189:
        print("You answered this Question correctly")
        break
        
 
    print("Your Answer is wrong try again ")  
