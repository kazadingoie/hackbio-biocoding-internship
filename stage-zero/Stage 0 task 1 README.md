This folder contains my solution for the HackBio Stage Zero task
# My Information Code - README

## Overview
This Python script stores personal information in a dictionary and prints it in a structured format. It demonstrates the use of dictionaries and formatted string literals (f-strings) in Python.

## Steps Explained

### 1. Creating a Dictionary
The script starts by defining a dictionary called `My_info` to store personal details such as:
- Name
- Slack Username
- Email
- Hobby
- Country
- Discipline
- Preferred Programming Language

```python
My_info = {
    "Name": "Kazadi Ngoie",
    "Slack Username": "@Tatiene",
    "Email": "tatianangoie17@gamil.com",
    "Hobby": "Gaming",
    "Country": "South Africa",
    "Discipline": "Bioinformatics",
    "Preferred Language": "Python"
}
```

### 2. Printing the Information
To display the stored information in a structured way, the script uses an f-string inside a `print()` function:

```python
print(f"""
My Information:

    Name: {My_info['Name']}
    Slack Username: {My_info['Slack Username']}
    Email: {My_info['Email']}
    Hobby: {My_info['Hobby']}
    Country: {My_info['Country']}
    Discipline: {My_info['Discipline']}
    Preferred Language: {My_info['Preferred Language']}
""")
```

### 3. Output
When the script runs, it produces the following structured output:

```
My Information:

    Name: Kazadi Ngoie
    Slack Username: @Tatiene
    Email: tatianangoie17@gamil.com
    Hobby: Gaming
    Country: South Africa
    Discipline: Bioinformatics
    Preferred Language: Python
```

## How to Run the Code
1. Copy the code into a Python script file (e.g., `my_info.py`).
2. Open a terminal or command prompt and navigate to the file's directory.
3. Run the script using:
   ```sh
   python my_info.py
   ```
4. The structured information will be displayed in the terminal.

## Key Features
- **Dictionaries**: Uses a Python dictionary to store key-value pairs.
- **String Formatting**: Uses an f-string for clean output formatting.
- **Readability**: Presents information in a structured, easy-to-read format.

## Author
Kazadi Ngoie

## License
This script is open for personal and educational use.


