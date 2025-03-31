# quiz-game


print("Welcome to my quiz game!")

playing = input("Are you interested in playing game ? ")

if playing.lower() != "yes":
    quit()

print("Okay! Let's play :)"
score = 0

answer = input("Who is prime minister of india? ")
if answer.lower() == "narendra modi":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What is the capital of india? ")
if answer.lower() == "new delhi":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("where is taj mahal located? ")
if answer.lower() == "agra":
    print('Correct!')
    score += 2
else:
    print("Incorrect!")

answer = input("What is full form of ROM? ")
if answer.lower() == "read only memory":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

print("You got " + str(score) + " questions correct!")
print("You got " + str((score / 4) * 100) + "%.")
