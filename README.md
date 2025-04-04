# India_state_game

## 🗺️ India State Game
An interactive educational game built with Python and the Turtle graphics library. The objective is to correctly guess as many Indian states as possible within a user-defined time limit.
![india](https://github.com/user-attachments/assets/eef10536-e80d-49e0-b0a4-b9d16327b5f9)

## 📦 Features
- **🧠 Learn Indian states in a fun way.**
- **🕒 Customizable game duration (10 to 120 seconds).**
- **🖼️ Map of India with state labels displayed upon correct guesses.**
- **🏆 High score tracking saved across sessions.**
- **📄 Missed states saved in a CSV file for review.**

## 📂 Files
- **main.py – Main game logic.**
- **india_states.csv – CSV file with state names and corresponding coordinates.**
- **map of india.gif – Image used as the background map.**
- **high_score.txt – Stores the highest score achieved.**
- **missed_states.csv – Automatically generated list of states not guessed correctly.**

## ▶️ How to Run
Make sure you have Python installed (3.6+ recommended).
Install the required libraries:
  ```bash
pip install pandas
  ```

Ensure the following files are in the same directory:
  - main.py
  - india_states.csv
  - map of india.gif
  - Run the script:

  ```bash
python main.py
```
## 📝 Gameplay Instructions
- Enter how many seconds you'd like to play (between 10 and 120).
-  A map of India will appear.
-  Start typing state names — correct answers will be labeled on the map.
-  Type Exit to quit early.
-  At the end, your score and the high score will be shown.
-  A file missed_states.csv will be created with all the states you didn't guess.
