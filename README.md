# security
One of my main focuses with Python is data security.  So this repository holds all of my practice concerning that. 

Code Louisville note: 
securemydata.py is a candidate for my final project for the class. The program allows for the user to add information to a file and look up information from the file and is accompanied by a basic CC encryption and decryption function. 

To change the the encryption just change the shift, but your shift back must equal the first shift in order to return the original value. This program can be expanded to encode any sort of information. I used health care information as an example of data that is personal and would have some reason to be encrypted. 

The most interesting part of the file is the encryption process. It indexes the characters on the ascii table and uses the modulo function to create a loop of sorts so it is only working with the english alphabet. You'll see a function for both uppercase and lowercase characters. There is a function to allow the program to accept numbers and random characters, but the random characters are not encoded. 
