# 08 Fire Switch

The Switch Fire VFX function allows you to smoothly fade fire effects in and out during gameplay.

It provides controlled fire activation and deactivation with seamless transitions, making it ideal for abilities, status effects, transformations, or other in-game events that require dynamic fire appearance changes.

## Step 01

Under Event Graph Tab, enable input at the event begin play

<img width="891" height="692" alt="image" src="https://github.com/user-attachments/assets/c45efc79-cd25-4066-bac8-932117125f5a" />

## Step 02

Add Keyboard to test the effect, Here's an example using Key 1 and flop-flop

<img width="685" height="447" alt="image" src="https://github.com/user-attachments/assets/a8d69942-1834-4266-999b-5430e8ce127d" />


## Step 03

Add timeline function and connect flip-flop to Play from Start and Reverse from End

<img width="906" height="560" alt="image" src="https://github.com/user-attachments/assets/46216ca1-f854-43a4-8e81-b2b7fd36e2b2" />


## Step 04

Open timeline and add a new float curve, with (0,1) and (1,0)

<img width="1085" height="485" alt="image" src="https://github.com/user-attachments/assets/267418de-be8b-4a08-b748-258e9666f704" />

## Step 05

Add Switch Fire VFX after Update, and connect New Track 0 to Animation (0-1)

<img width="951" height="631" alt="image" src="https://github.com/user-attachments/assets/84d95947-0bb3-47e7-9c46-b160fd7e3d10" />

## Step 06

Compile and save, now hit play mode and test Key 1 to see if the fire switch.

