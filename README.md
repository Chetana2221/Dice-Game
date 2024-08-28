# Dice-Game
we will be building a Dice Game Project using Java and XML in Android. The Dice Game is based on a two-player game. Both players roll the dice and the player who gets the highest phase value will win the game. There will be a single activity in this application. This activity will show the two player’s name and their dice. The result will be displayed on the top and there will be a roll button at the bottom.

Step by Step Implementation
Step 1: Create a New Project

To create a new project in Android Studio please refer to How to Create/Start a New Project in Android Studio. Note that select Java as the programming language.

Step 2: Before going to the coding section first you have to do some pre-task

Dice Images: All the dice images are listed below. Save them in your drawable folder in resources. Go to the app > res > drawable and paste the following files:
Dice 1
Dice 2
Dice 3
Dice 4
Dice 5
Dice 6

Step 3: Working with the activity_main.xml file

The XML codes are used to build the structure of the activity as well as its styling part. It contains a TextView at the very top of the activity to show the game result. Then it contains two ImageView, each with a TextView for the Player name and the image of the rolled dice. At the bottom of the activity, there is a Button to roll the dice. Below is the code for the activity_main.xml file.

Step 4: Working with the MainActivity.java file

We will create an array inside the Java file that will contain all the images of the dice. Then we will call onClickListener() for the button and generate two random numbers using the Random function. Then we will check the two numbers and display the result respectively. Also, we will set the two images from the array. Below is the code for the MainActivity.java file. Comments are added inside the code to understand the code in more detail.
