# 🏏 Cricket Match Analysis

This project fetches and analyzes cricket match data from an external API. It determines the highest team scores and counts the number of matches with total scores above 300. 🚀🌐📊

## Features

- Fetch cricket match data from a specified API.
- Analyze match data to find the highest scores by teams.
- Count the number of matches with combined scores above 300.

## Prerequisites

- Java 8 or higher
- JSON library (org.json)

## How to Run

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Er-Abhay-FSD/Cricket_Analysis.git
    cd Cricket_Analysis
    ```

2. **Compile the Java files**:

    ```bash
    javac -cp .:json-20210307.jar com/crickbuzz/cricketmatches/*.java
    ```

3. **Run the main program**:

    ```bash
    java -cp .:json-20210307.jar com.crickbuzz.cricketmatches.CricketAnalysis
    ```

## Project Structure

```plaintext
cricket-match-analysis/
├── com/
│   └── crickbuzz/
│       └── cricketmatches/
│           ├── CricketAnalysis.java
│           └── CricketAnalysisTest.java
├── json-20210307.jar
├── README.md
└── .gitignore
