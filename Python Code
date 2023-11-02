import random
random1 = random.randint(0, 100)

i = 0
score = 0

print("Hello, welcome to the number guessing game.")
print("Try to guess a number between 1-100")
print("If you wish to Quit enter 0.")

while i >= 0:
    guess = int(input("Guess the number: "))
    i += 1
    if guess == 0:
        if score > 0:
            print(f"You guessed the number correctly {score}/",i-1,"times.")
        else:
            print("The correct number was not guessed at all.")
        break

    elif guess == random1:
        print("You got it correct, have another turn.")
        score += 1
        random1 = random.randint(0, 100)
    elif guess >= random1:
        print("Too high, try again")
    else:
        print("Too low, try again")
