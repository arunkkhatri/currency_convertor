# currency_convertor
An API to convert an amount from one currency code to desired currency based on the real time currency exchange rates

# README #

### Contributing Guidelines ###

* Fork repo

* check generated ui at: http://localhost:8000/<api_endpoint>/

#### Initial Setup ####
In Terminal
* Install python and pip using command:
    1. sudo apt-get update
    2. sudo apt-get install python3
    2. sudo apt-get install python3-pip

* Fork the Repository:
    1. git clone ---

* cd into the cloned repository and install & activate virtual environment:
    1. cd currency_convertor
    2. pip3 install virtualenv
    3. virtualenv venv
    4. source venv/bin/activate

* Install Django and additional requirements:
    1. pip3 install django
    2. pip3 install -r requirements.txt
    3. python3 manage.py migrate


#### Running Application ####
After installing application and its dependencies:

* run the application with: `python manage.py runserver` and test the api endpoint with required input at:
    http://127.0.0.1:8000/convert

<!-- sample api request:
    http://127.0.0.1:8000/convert?amount=12.23&src_currency=USD&dest_currency=INR&reference_date=2020-02-26 -->
