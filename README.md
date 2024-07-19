# 🏏 Cricket Match Analysis

This project fetches and analyzes cricket match data from an external API. It determines the highest team scores in one innings and counts the number of matches with total scores above 300. 🚀🌐📊

## Problem Statement

You will be given an API which contains a list of recent cricket matches with their data. The task is to print a few key results from the given set of matches.

## API Description

Here is the API curl link:

```bash
curl --location 'https://api.cuvora.com/car/partner/cricket-data' \
--header 'apiKey: test-creds@2320'
```

# API Documentation: Match Data

This API provides a list of matches with detailed information. Each match entry includes various fields that describe the match's status, teams, and scores.

## GET /matches

### Description

Retrieve a list of matches with their respective data.

### Response Fields

- **id**: Unique identifier for the match.
- **dateTimeGMT**: Date and Time of the match in GMT.
- **matchType**: Type of the match (e.g., T20, ODI, Test Match).
- **status**: Result of the match (e.g., "Team A won by 10 runs").
- **ms**: Match Status
  - `Result`: Match result is obtained.
  - `Fixture`: The match is scheduled but not yet started.
  - `Ongoing`: The match is currently in progress.
- **t1**: Name of Team 1.
- **t2**: Name of Team 2.
- **t1s**: Score of Team 1.
- **t2s**: Score of Team 2.

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
    java -cp .:json-20210307.jar com.crickbuzz.cricketmatches.Main
    ```

## Project Structure

```plaintext
Cricket_Analysis/
├── com/
│   └── crickbuzz/
│       └── cricketmatches/
│           ├── CricketAnalysis.java
│           └── Main.java
├── json-20210307.jar
├── README.md
└── .gitignore
```

## Example Output

```plaintext
Highest Score: "350" and Team Name is: "Team A"
Number Of Matches with total 300 Plus Score: "5"
```
## Contributing
Contributions are welcome! Please create an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to replace https://github.com/Er-Abhay-FSD/Cricket_Analysis.git with your actual GitHub repository URL. If you have any questions or need further assistance, please don't hesitate to ask!

```plaintext

This `README.md` should provide a clear guide for users to understand and run your project.

```
