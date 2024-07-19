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
