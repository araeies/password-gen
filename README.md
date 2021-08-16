# password-gen
password generator 


import random
from random import randint

password = " "

pass_len = int(input("what do you want your password length to be? "))

for i in range(pass_len):
	i = chr(randint(33, 122))

	password = str(password) + i

print(password)
