 

# Risk Tolerance Reanalysis Using AI Agentic Workflow (AI-Agents-For-Reanalysis-of-Risk-Tolerance)

## Overview
This project aims to reevaluate user risk tolerance based on provided JSON data. It involves analyzing relevant financial information and generating a new JSON file with updated risk tolerance values. The project employs Microsoft Autogen and Llama3.1 8b from the Groq API for a comprehensive analysis.

## Table of Contents
- [Objective](#objective)
- [Technologies Used](#technologies-used)
- [Steps](#steps)
- [Usage](#usage)
- [License](#license)

## Objective
The primary goal is to develop a system that:
1. Reads user data from a JSON file.
2. Analyzes financial information, investment goals, and demographic data.
3. Generates updated risk tolerance values based on the analysis.

## Technologies Used
- **Programming Language**: Python
- **Language Model**: [Llama3.1 8b](https://groq.com) from Groq API
- **Agentic Framework**: Microsoft Autogen
- **Data Format**: JSON

## Steps
### Step 1: Read the JSON File
- Create an agent to read and extract data from `userForm.json`, which includes user demographics, financial information, risk tolerance, and investment preferences.

### Step 2: Create a Group of Agents for Reanalysis
- Develop a group of AI agents to:
  - Reanalyze specific data points such as financial goals, investment strategy, and portfolio structure.
  - Use the analyzed information to reassess user risk tolerance based on:
    - Current income, investments, and debt levels.
    - Investment goals and preferences.
    - Existing tolerance levels and target values.

### Step 3: Write a New JSON File
- Each agent provides an updated analysis of factors affecting risk tolerance.
- A final agent compiles the findings and writes a new JSON file containing updated risk tolerance values, reflecting changes in the user's financial situation or risk parameters.

