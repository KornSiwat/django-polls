## Django Polls

This project is a web application with admin page to make polls
which allow users to vote and track the results in the webpage.

---

## Prerequisite

These resources are needed in order to run the program:

- `Python (ver.3.6 or newer)` [download site](https://www.python.org/downloads/)
- `Python modules listed in` [requirement file](requirements.txt)

## Installation

### Step 1: Cloning the repository

    Open the Terminal and type the following command:

        git clone https://github.com/KornSiwat/django-polls

### Step 2: Install required python3 modules

    Open the Terminal and type the following command:

        On MacOS and Linux:

            pip3 install -r requirements.txt

        On Windows:

            pip install -r requirements.txt

### Step 3: Migrating Data

    Type the following command in the Terminal:

        On MacOs and Linux:

            python3 manage.py migrate

        On Windows:

            python manage.py migrate
            
### Step 4: Creating a config file

    Type the following command in the Terminal:
    
        touch .env
        
### Step 5: Adding required config to the config file

   #### Edit .env file create these variable and assign your prefering config to these following variable name:
    
        ⦿ SECRET_KEY: String
        
        ⦿ DEBUG: Bool
        
        ⦿ DB_NAME: String
        
        ⦿ TIME_ZONE: String
            
## How to run locally

### Step 1: Execute runing command

    Open the Terminal and type the following command:

        On MacOS and Linux:

            python3 manage.py runserver

        On Windows:

            python manage.py runserver
    
### Step 2: Look for the address and port on your console

    An address and port will be printed on the console.    
    
    Django run on port 8000 by default.

## Contact

    Siwat Ponpued
        Tel: 0615453292
        Line-id: k41763
        email: siwat@siwat.dev
