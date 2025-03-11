# Project Title

![Project Image](path/to/your/image.png)

## Overview
This project is a cutting-edge application that leverages the power of OpenAI's GPT models, PostgreSQL for database management, and advanced AI agents to provide intelligent and dynamic responses to user queries. By integrating LangChain graphs and AI agents, the application offers a seamless and efficient way to interact with data and generate insights. Whether you're querying a database or asking complex questions, this tool is designed to deliver accurate and context-aware results.

---

# Project Setup

## Step 1: Install Python 3.9 or Higher
Download and install Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)

## Step 2: Install Dependencies
Run the following command to install the required dependencies:

```bash
pip install -r requirements.txt
# Project Setup

## Step 1: Install Python 3.9 or Higher
Download and install Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)

## Step 2: Install Dependencies
Run the following command to install the required dependencies:

```bash
pip install -r requirements.txt
```
# Application Setup Guide

## Step 3: Set OpenAI API Key in Environment

Add your OpenAI API key as an environment variable:

### Windows Command Prompt
```cmd
set OPENAI_API_KEY=your_openai_api_key
```
### Windows PowerShell
```
$env:OPENAI_API_KEY="your_openai_api_key"
```
### Linux/Mac
```
export OPENAI_API_KEY=your_openai_api_key
```

## Step 4: Add PostgreSQL Details
In app.py, update the PostgreSQL connection details with your database credentials:

```
DATABASE = {
    "dbname": "your_dbname",
    "user": "your_username",
    "password": "your_password",
    "host": "localhost",
    "port": 5432
}
```

## Step 5: Run the Application
Start the application by running:

```
python app.py
```

## Step 6: Ask Your Text Question
Once the application is running, ask your question directly in the terminal:
```
> how many model are there in garage?
```