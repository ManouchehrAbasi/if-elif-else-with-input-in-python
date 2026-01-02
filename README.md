# if-elif-else-with-input-in-python

We can combine conditional statements in Python with input and see the desired results by entering the desired value in the terminal.

example:

x = int(input("Enter your weight:"))

if x < 60:

    print(x, "kg means:", "you are thin!")
    
    print("You need to make changes in your lifestyle.")


    
elif x > 90:

    print(x, "kg means:", "you are fat!")
    
    print("You must exercise.")

    
else:

    print(x, "kg means:", "Your weight is ideal.")



output1:

Enter your weight:55

55 kg means: you are thin!

You need to make changes in your lifestyle.



output2:

Enter your weight:95

95 kg means: you are fat!

You must exercise.



output3:

Enter your weight:70

70 kg means: Your weight is ideal.

    
