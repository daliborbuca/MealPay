# MealPay
import random

# Ask the user to input a list of names, separated by a comma and space.
names_string = input("Give me everybody's names, separated by a comma and a space. ")

# Split the string into a list of names.
names = names_string.split(", ")

# Use random.choice() to randomly select one person from the list.
person_who_will_pay = random.choice(names)

# Print the name of the chosen person along with the specific phrase.
print(person_who_will_pay + " is going to buy the meal today!")

