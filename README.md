# Homework-01.02.2024-Q3
Homework for Mr Tauheed

user_info = {}

user_info["name"] = input("What is the user's name? ")
user_info["age"] = input("What is the user's age? ")
user_info["country_of_birth"] = input("What is the user's country of birth? ")
user_info["known_for"] = input("What is the user known for? ")

print("\nUser Information:")
for key, value in user_info.items():
    print(f"{key.capitalize()}: {value}")
