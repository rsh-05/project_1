# project_1
just a general quiz

print("Welcome to General Knowledge Quiz game")
ask = input("Do you want to play? (Yes/No) : ")
if ask.lower() == "yes":
    print("Great, Let's Play")
elif ask.lower() == "no":
    print("Okay then, You are DUMB anyways :)")
    quit()
else:
    print("I even mentioned to type 'Yes or No' only but You are too DUMB to play this quiz, GET LOST!")
    quit()
score = 0

q1 = input(("Question 1 - What is the Derivative of Sinx? : "))
if q1.lower() == "cosx":
    print("Correct Answer")
    score += 1
else:
    print("Wrong Answer")

q2 = (input("Question 2 - What is the constant parameter in Isobaric process in Thermodynamics? : "))
if q2.lower() == "pressure":
    print("Correct Answer")
    score += 1
else:
    print("Wrong Answer")

q3 = input("Question 3 - Who invented Calculus? : ")
if q3.lower() == "isaac newton" or q3.lower() == "newton" or q3.lower() == "sir isaac newton":
    print("Correct Answer")
    score += 1
else:
    print("Wrong Answer")

print(f"Your total score is {score} out of 3")
