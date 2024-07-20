## U.S. States Game
This project is a fun and interactive game to test your knowledge of U.S. states. Using the Turtle graphics library and Pandas for data handling, this game prompts the user to input the names of U.S. states and places them on a blank map of the United States.

## Features
Interactive map of the U.S. with state names.
User input handling to check and display correct state names.
Saves a CSV file of states to learn if the user exits before completing the game.

## Prerequisites
Before you begin, ensure you have met the following requirements:

Python 3.x
Turtle graphics library
Pandas library
You can install the required libraries using pip:

sh
Copy code
pip install pandas turtle
Usage
Clone the repository to your local machine.
sh
Copy code
git clone https://github.com/your-username/us-states-game.git
Navigate to the project directory.
sh
Copy code
cd us-states-game
Ensure you have the 50_states.csv file with the correct state data and coordinates.
Run the main.py script.
sh
Copy code
python main.py
Follow the prompts on the screen to enter state names. Type "Exit" to quit the game and save the states you need to learn.


## How It Works
The game displays a blank map of the United States.
The user is prompted to input the name of a state.
If the state name is correct, it is displayed on the map in its correct location.
The game continues until all 50 states are correctly named or the user exits the game.
If the user exits, a CSV file (States_to_learn.csv) is generated with the names of the states that were not guessed.
## Files
main.py: The main script to run the game.
50_states.csv: CSV file containing state names and their coordinates.
blank_states_img.gif: Image file of the blank U.S. map.
