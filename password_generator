import random
letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
symbols = ['!', '#', '$', '%', '&', '(', ')', '*', '+']
print("Welcome to my Password Generator!")
print("This code is written by J0ey")
nr_letters= int(input("How many letters would you like in your password?\n")) 
nr_symbols = int(input(f"How many symbols would you like?\n"))
nr_numbers = int(input(f"How many numbers would you like?\n"))
password_ls = []
for letter in range(nr_letters):
    picked_letters = random.choice(letters)
    password_ls.append(picked_letters)
for symbol in range(nr_symbols):
    picked_symbols = random.choice(symbols)
    password_ls.append(picked_symbols)
for number in range(nr_numbers):
    picked_numbers = random.choice(numbers)
    password_ls.append(picked_numbers) 
random.shuffle(password_ls)
finalpassword = ""
for character in password_ls:
    finalpassword += character
print(finalpassword)
