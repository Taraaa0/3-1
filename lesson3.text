# 3-1
# 1.What do you think the if does to the code under it?  It will inform the computer to know what it should do with informations (whether run it or not)
# 2.What is the purpose of indenting in the if statement? How can we tell what code is enclosed in an if branch and what code is not? The purpose of indent is to know the information belonging to the if statement and the computer should run it when if statements are true. If there is an indent every information lined up in the same area is for the if statement and if you start a new line without indent it means it doesn't belong to the if statement.
# 3.Change the initial locations of the objects and get the program to output the same thing
robot_location = 40
ball_location = 50
goal_location = 15
have_ball = False

if robot_location < ball_location:
    print("Almost at the ball")

if robot_location > goal_location:
    print("You are beyond the goal.")

if robot_location == goal_location:
    print("The robot is at the goal.")

robot_location += 10

if robot_location == goal_location:
    print("At the goal.")

if robot_location == ball_location:
    print("At the ball")
    print("Picking up the ball.")
    have_ball = True
    print("Now make your way to the goal.")

robot_location -= 35

if robot_location < goal_location:
    print("You went too far.")

if robot_location == goal_location and have_ball is True:
    print("You scored a goal!")
    have_ball = False

## What do the operators += and -= do? += adds the value of the right -= subtracts the value of the right from the left number



print("Hey what is your name?")
name=input()
print(f"Ok {name} how old are you?")
age=int(input())
if age<16:
    print("You can't drive.")
if age<18:
    print("You can't vote.")
if age<21:
    print("You can't rent a car.")
if age==21:
    print("You can do anything that's legal.")

#input - age=15   output= you can't drive, you can't vote, you can't rent a car
#input - age=16   output=you can't vote, you can't rent a car
#input - age =17  output=you can't vote, you can't rent a car
#input - age=18   output=you can't rent a car
#...
#input - age=21   output=Yoy can do anything that's legal
