create a new Python file and name it "user_input.py"
Use the input() function to ask the user for their name and store it in a variable called "name".
Use the input() function to ask the user for their age and store it in a variable called "age".
Use the input() function to ask the user for their location and store it in a variable called "location".
Print out a personalized message using the user's name, age, and location. For example: "Hello [name], you are [age] years old and live in [location]."
Save and run the program to see the output.

# Creating a Python file "user_input.py" with the requested code
code =
# user_input.py

# Asking for user's name, age, and location
name = input("What is your name? ")
age = input("How old are you? ")
location = input("Where are you from? ")

name = "Joel"
age = "22"
location = "Mombasa"

# Printing the personalized message
print(f"Hello {name}, you are {age} years old and live in {location}.")

"Hello Joel,you are 22 yeras old and live in Mombasa

# Save the file
file_path = "/mnt/data/user_input.py"
with open(file_path, "w") as file:
    file.write(code)

file_path
