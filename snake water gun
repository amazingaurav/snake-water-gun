# snake water gun
# input 10 times
# snake > water
# water > gun
# gun > snake
# while loop
# random choice function

import random

choices = ("water", "snake", "gun")


i=0
user_count = 0
comp_count = 0
while i <10:
    print("tries left are ", 10 - i)
    user_input = input(f"enter the choice from {choices} : ")
    i += 1
    comp_input = random.choice(choices)
    if user_input == comp_input:
        print(f"its a tie as computer's input was {comp_input}")
    elif user_input == "water":
        if comp_input == "gun":
            user_count +=1
            print(f"you won ! as computer's input was {comp_input} and your input was {user_input}")
        elif comp_input == "snake":
            comp_count += 1
            print(f"you loose ! as computer's input was {comp_input} and your input was {user_input}")

    elif user_input == "snake":
        if comp_input == "gun":
            comp_count += 1
            print(f"you loose ! as computer's input was {comp_input} and your input was {user_input}")
        elif comp_input == "water":
            user_count += 1
            print(f"you won ! as computer's input was {comp_input} and your input was {user_input}")
    elif user_input == "gun":
        if comp_input == "snake":
            user_count += 1
            print(f"you won ! as computer's input was {comp_input} and your input was {user_input}")
        elif comp_input == "water":
            comp_count +=1
            print(f"you loose ! as computer's input was {comp_input} and your input was {user_input}")

    else:
        print("invalid input. please enter again ")
        i = i-1

print(f"comp won {comp_count} times and you won {user_count} times")
