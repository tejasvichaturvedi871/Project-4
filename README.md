# Project-4
#  Program 4: WAP that accepts a character and performs the following:
#  a. print whether the character is a letter or numeric digit or a special character.
#  b. if the character is a letter,print whether the letter is uppercase or lowercase.
#  c. if the character is a numeric digit, prints its name in text
code= character = input("enter data")
if character >='A' and character<='Z':
print("uppercase letter")
elif character >='a' and character<='z':
print("lowercase letter")

elif character >='0' and character<='9':
print("numeric digit")
n = int(character)
dict = {0:'zero',1:'first',2:'two',3:'three',4:'four',5:'five',6:'six',7:'seven',8:'eight',9:'nine'}
print(dict[n])
else:
print("special character")
