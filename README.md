# Online Quiz App (Console - Java)

A clean, beginner-friendly **console-based quiz application** built with Java. It demonstrates core concepts like **loops**, **control flow**, and **Java Collections** (List, Map, Iterator), plus **shuffle** and **sorting** for a more engaging experience. The app supports a **leaderboard** saved locally (CSV), so you can replay and improve your score.   

##  Features  ##
- **Java Basics Quiz** with explanations after each question
- **Shuffle** questions & options on every run for fairness
- **Flexible length**: choose how many questions to attempt
- **Instant feedback** (correct/incorrect) and final **grade & percentage**
- **Leaderboard (Top 5)** saved to scores.csv with timestamp
- **Beginner-friendly** file structure and commands

##  Tech Stack  ##
- Language: **Java (JDK 17+)**
- Runtime: **Console**
- Data: **CSV** for scores (no external DB)

##  Getting Started  ##

### 1) Compile & Run
```bash
cd OnlineQuizApp\src
javac *.java
java QuizApp
```
### 2) How to Play ###
- Enter your name.
- Choose Java Basics quiz.
- Select number of questions.
- Answer using A–D or 1–4.
- View results with explanations and choose to save score.
- Check Leaderboard from the main menu.

### 3) Screenshots (add yours) ###

![output](assests/output1.png)
![output](assests/output2.png)
![output](assests/output3.png)
![output](assests/output4.png)


## Sample Questions Covered ##
- Java loops & enhanced for-loop
- Collections: ArrayList, Map, Iterator
- Collections.shuffle & Collections.sort
- switch vs if-else
(Easily extend the bank in QuestionBank.java.)

## Extend the App ##
- Add new categories (e.g., OOP, Exceptions, Streams)
- Add timed questions
- Persist questions to JSON / CSV
- Export results as PDF

## .gitignore ##
- Excludes compiled .class files and local scores.csv.
