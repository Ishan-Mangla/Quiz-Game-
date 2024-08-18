Computer Quiz Game
This is a simple command-line quiz game designed to test your knowledge about computer terminology and concepts.
The game prompts the user with multiple-choice questions related to computer hardware, software, and fundamental technologies.

**Features**
1. Interactive command-line interface
2. Ten questions covering various computer-related topics
3. Scoring system to track correct answers and calculate the percentage score
4. Feedback for each answer to help users learn and improve

**How to Play?**

**Step1**
-> Run the script in a Python environment.

**step2**
->Answer each question by typing your response and pressing Enter.

**step3**
->After all questions are answered, your score and percentage will be displayed.

**Requirements**
Python 3.x

**Installation**
No installation is required. Simply download or clone the repository and run the quiz.py script.

#HERE IS THE CODE

print("Welcome to my computer quiz!")

playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("Okay! Let's play :)")
score = 0

answer = input("What does CPU stand for? ")
if answer.lower() == "central processing unit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does GPU stand for? ")
if answer.lower() == "graphics processing unit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does RAM stand for? ")
if answer.lower() == "random access memory":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does GB stand for in the world of computers? ")
if answer.lower() == "gigabyte":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("Who is the father of Computers? ")
if answer.lower() == "charles babbage":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("The two kinds of main memory are: ")
if answer.lower() == "rom and ram":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What is the full form of SSL? ")
if answer.lower() == "secure socket layer":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What is the full form of HTML? ")
if answer.lower() == "hypertext markup language":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What is the full form of HTTP? ")
if answer.lower() == "hyper text transfer protocol":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What is the full form of UPS? ")
if answer.lower() == "uninterruptible power supply":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")


print("You got " + str(score) + " questions correct!")
print("You got " + str((score / 10) * 100) + "%.")
