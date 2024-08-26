# Computer-Quiz

print("Welcome to my computer quiz!")

playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("Okay! Let's play :)")
score = 0
#1.

answer = input("What does CPU stand for? ")
if answer.lower() == "central processing unit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")
#2.

answer = input("What does GPU stand for? ")
if answer.lower() == "graphics processing unit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

#3.
answer = input("What does RAM stand for? ")
if answer.lower() == "random access memory":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

#4.

answer = input("What does PSU stand for? ")
if answer.lower() == "power supply":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

#5.

answer = input("What is the basic unit of information in computing? ")
if answer.lower() == "bit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

#6.

answer = input("Which of the following is an example of secondary storage? ")
if answer.lower() == "hard disk drive":
    print('Correct!')
    score += 1 
else:
    print("Incorrect!")

#7.

answer = input("Name a programming language that starts with py? ")
if answer.lower() == "python":
    print('Correct!')
    score += 1 
else:
    print("Incorrect!")

#8. 

answer = input("What is the main purpose of an operating system? ")
if answer.lower() == "To manage computer resources":
    print('Correct!')
    score += 1 
else:
    print("Incorrect!")

#9.   

    answer = input("Which component of a computer is responsible for displaying graphics on the screen?")
if answer.lower() == "graphics processing unit":
    print('Correct!')
    score += 1 
else:
    print("Incorrect!")
    
#10.

answer = input("Name a input device that starts with the later K")
if answer.lower == "keyboard":    
    print('Correct')
    score += 1
else:
    print("Incorrect!")
    
#11.

answer = input("What does HTML stand for?")
if answer.lower == "hypertext markup language":    
    print('Correct')
    score += 1
else:
    print("Incorrect!")
    
#12.

answer = input("What is the purpose of a firewall in computer networks?")
if answer.lower == "to prevent unauthorized access":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

#13.

answer = input("Which programming language is often used for data analysis and scientific computing starting with letter P?")
if answer.lower == "python":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

#14.

answer = input("Input device starting with the letter M?")
if answer.lower == "mouse":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")
    
#15.

    answer = input("What is the purpose of a VPN (Virtual Private Network?")
    if answer.lower == "establishing a secure connection over a network":
        print('Correct!')
        score += 1
    else:
        print("Incorrect!")
        
#16.

answer = input("What is the purpose of an input/output port on a computer?")
if answer.lower == "connecting external devices for data transfer":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")
    
#17.

answer = input("What is the purpose of a storage device?")
if answer.lower == "to store data permanently": 
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

#18.

answer = input("What does the term “WAN” stand for in computer networking?")
if answer.lower == "wide area network":
    print('Correct!')
    score += 1
else:
    print("Incorrect!") 
    
#19.

answer = input("What is the purpose of a software update?")
if answer.lower == "fixing bugs and adding new features to software programs ":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")


#20.

answer = input("What is the purpose of a network protocol?")
if answer.lower == " Defining rules for communication between devices on a network":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")
    
print("You got " + str(score) + " questions correct!")
print("You got " + str((score / 20) * 100) + "%.")
#be mindful that this code above print("You got " + str((score / 4) * 100) + "%.") the 5 was a 4 increase digit to add more questions.

