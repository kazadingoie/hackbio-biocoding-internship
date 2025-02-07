# Team Information

## Overview
This repository contains a Python script that structures and prints detailed information about a team of individuals, including their names, Slack usernames, email addresses, hobbies, countries, disciplines, and preferred programming languages.

## How I Created This Code
The Python script was developed to store team members' details using a list of dictionaries. Each dictionary represents an individual team member and contains the following fields:
- **Name**: The full name of the team member.
- **Slack Username**: The team member's username on Slack.
- **Email**: The contact email address.
- **Hobby**: A personal interest or hobby.
- **Country**: The team member's country of residence.
- **Discipline**: The field of study or expertise.
- **Preferred Language**: The programming language they prefer.

The script iterates through the list and prints each member's details in a structured format for easy readability.

## Code Implementation
```python
# List of dictionaries to store team members' details
team_info = [
    {
        "Name": "Kazadi Ngoie",
        "Slack Username": "@Tatiene",
        "Email": "tatianangoie17@gmail.com",
        "Hobby": "Gaming",
        "Country": "South Africa",
        "Discipline": "Bioinformatics",
        "Preferred Language": "Python"
    },
    {
        "Name": "Bezaleel Akinbami",
        "Slack Username": "@Bez",
        "Email": "bezaleelakinbami16@gmail.com",
        "Hobby": "Gaming",
        "Country": "Nigeria",
        "Discipline": "Bioinformatics ",
        "Preferred Language": "R"
    },
    {
        "Name": "Hana Nadir",
        "Slack Username": "@Hana",
        "Email": "hananadir04@gmail.com",
        "Hobby": "Reading",
        "Country": "Sudan",
        "Discipline": "Medecinal chemistry and drug discovery",
        "Preferred Language": "Python"
    },
    {
        "Name": "Onyinye Maryrose Ugwu ",
        "Slack Username": "@Onyinye",
        "Email": "monyinye80@gmail.com",
        "Hobby": "Travelling",
        "Country": "Nigeria",
        "Discipline": "Zoology",
        "Preferred Language": "Python"
    },
    {
        "Name": "Sanzida Akhter Anee",
        "Slack Username": "@ethan_b",
        "Email": "aneesanzidaakhter@gmail.com",
        "Hobby": "Blogging",
        "Country": "Sudan",
        "Discipline": "Bioinformatics",
        "Preferred Language": "Python"
    }
]

# Printing the structured team details
print("Team Members Information:\n")

for member in team_info:
    print(f"Name: {member['Name']}")
    print(f"Slack Username: {member['Slack Username']}")
    print(f"Email: {member['Email']}")
    print(f"Hobby: {member['Hobby']}")
    print(f"Country: {member['Country']}")
    print(f"Discipline: {member['Discipline']}")
    print(f"Preferred Language: {member['Preferred Language']}")
    print("-" * 40)  # Separator for better readability
```

## Output
When the script is executed, it prints the information of all team members in a structured format:
```
Team Members Information:

Name: Kazadi Ngoie
Slack Username: @Tatiene
Email: tatianangoie17@gmail.com
Hobby: Gaming
Country: South Africa
Discipline: Bioinformatics
Preferred Language: Python
----------------------------------------
Name: Bezaleel Akinbami
Slack Username: @Bez
Email: bezaleelakinbami16@gmail.com
Hobby: Gaming
Country: Nigeria
Discipline: Bioinformatics
Preferred Language: R
----------------------------------------
Name: Hana Nadir
Slack Username: @Hana
Email: hananadir04@gmail.com
Hobby: Reading
Country: Sudan
Discipline: Medecinal chemistry and drug discovery
Preferred Language: Python
----------------------------------------
Name: Onyinye Maryrose Ugwu
Slack Username: @Onyinye
Email: monyinye80@gmail.com
Hobby: Travelling
Country: Nigeria
Discipline: Zoology
Preferred Language: Python
----------------------------------------
Name: Sanzida Akhter Anee
Slack Username: @ethan_b
Email: aneesanzidaakhter@gmail.com
Hobby: Blogging
Country: Sudan
Discipline: Bioinformatics
Preferred Language: Python
----------------------------------------


## How to Run the Script
1. **Clone the Repository**
   git clone https://github.com/your-username/team-info.git
2. **Navigate to the Project Directory**
   cd team-info
3. **Run the Script**
   python script.py
   


