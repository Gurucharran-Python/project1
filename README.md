correct_number=3
while True:
    guessed_number=int(input("guess the number:"))
    if (correct_number==guessed_number):
        print("Congragulations!! :D")
        break
    else:
        print("Try again :(")
