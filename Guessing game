import random as rd
print('''This is a Guessing game where you have only 3 chances to guess my correct number.
                               Good Luck!!
      ''')
guess = True
n = 50
guess_limit = 3
guess_count = 0
a = int(n * rd.random()) + 1
while guess_count < guess_limit:
    if guess_count == 0:
        guess = int(input("Guess My Number(First Chance): "))
    if guess_count == 1:
        guess = int(input("Guess My Number(Second Chance): "))
    if guess_count == 2:
        guess = int(input("Guess My Number(Last Chance): "))
    if guess < a:
        print('     [Number is too small]')
    if guess > a:
        print('     [Number is too large]')
    elif guess == a:
        print('     [Good Job! You are an excellent guesser!]')
        break
    if guess > n:
        print('     [You should guess a number between 0 and 50]')
    guess_count += 1
    if guess_count > 2:
        print('')
        print('[!!Sorry you lost your 3 chances!!]')
        print('')
        print(f'[The correct number was: {a} , "Better luck next time :)" ]')
