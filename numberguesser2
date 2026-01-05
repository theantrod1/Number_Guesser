import random
random_number = random.randrange(1, 101)
guesses = 0
while True:
    guesses += 1
    guess = input("Make a guess: ")
    if guess.isdigit():
        guess = int(guess)
    else:
        print("Type a number please")
        continue

    if guess == random_number:
        print("correct")
        break
    elif guess < random_number:
        print("higher")
    elif guess > random_number:
        print("lower")
        continue

if guesses > 1:
    print(f"You got in {guesses} guesses")
else:
    print(f"You got it in {guesses} guess")
