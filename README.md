# sport-predict
Java-based sport matchup predictor program that analyzes current-season team statistics and previous results to generate projected scores and winners

# The Problem
I like following sports (especially football, soccer, and basketball) and predicting game outcomes, but comparing team performances and power rankings across multiple different sources can be both frustrating and annoying. I want a more organized and efficient way to evaluate upcoming matchups and use available data to make score predictions for any game between two NCAA, NBA, or NFL teams. This can also be used for making more informed predictions for gambling purposes.

# How it Works
The program allows users to select any two teams and generates a projected score and winner based on their current-season form.

The MVP will:
Maintain a database of teams and their current-season stats, including wins/losses, points scored/allowed, and average point differential.
Allow users to select two teams.
Store previous game results and scores in CSV files.
Analyze team statistics to calculate projected scores and determine a likely winner.

# Tech Stack
Languages: Java, Bash.
Libraries: java.io, java.util, and java.time.
External Tools: Git, GitHub, IntelliJ IDEA, and terminal (Ubuntu).
Data Storage: CSV files for relevant team history.
Future Integrations: Sports statistic APIs and JSON parsing tools such as curl and jq.

# Setup

Requirements:
- Java
- Git
- Bash-comparable terminal
Clone the repository:
git clone https://github.com/spoondl/sport-predict.git
cd sport-predict

Compile Java application:
javac -d out src/*.java

Run the application:
java -cp out Main

# Usage
1. Launch application through terminal
2. View available teams + statistics
3. Select two teams to compare
4. Application analyzes statistics
5. View projected score + winner

================================
       Sport-Predict
================================

Select Team 1: Philadelphia Eagles
Select Team 2: Dallas Cowboys

Analyzing matchup...

Philadelphia Eagles: 27
Dallas Cowboys: 20

Predicted Winner: Philadelphia Eagles
================================
# Roadmap

- [ ] Integrate a sports statistics reference API to automatically retrieve statistics and schedules.
- [ ] Incorporate weekly power rankings into prediction algorithm.
- [ ] Add prediction accuracy tracking by comparing predictions against IRL results.
- [ ] Implement H2H analysis using previous matchups between selected teams.

# Author
Sarosh Poondla
github.com/spoondl
