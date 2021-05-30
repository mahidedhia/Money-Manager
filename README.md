# Money-Manager
The money manager is a Python Tkinter application. It allows the user to keep a track of their earnings and expenses and analyze their money usage.

## Software Requirements
Python 3.9 - https://www.python.org/downloads/

MySQL - https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/

wkhtmltopdf - https://wkhtmltopdf.org/

## Installation
1. Download the project Repositories using Git or Github's web interface

2. Install the python package to create Virtual Environment
```
pip install virtualenv
```
3. In cmd, navigate to the directory in which you want to create the virtual environment and execute the following command to create a virtual environment
```
py -m venv <virtual-env-name>
```
4. Activate your Virtual environment
```
<virtual-env-name>\Scripts\activate.bat
```
5. Install Project Dependencies in your virtual environment
```
pip install -r requirements.txt
```
6. Open the MoneyManager.py file in a Text Editor or IDE and replace the words 'YOUR_USERNAME' and 'YOUR_PASSWORD' with your MySQL connection's username and password

7. In cmd, navigate to the directory that contains the project files and execute the following command
```
python MoneyManager.py
```
## Features and Functionalities
1. Add an earning or expense made in a particular category. Add an additional note if required.
2. View the analysis of monthly earnings and expenses category wise and analyze balance status over a period of one year.
3. View the earnings/expenses made on a selected date.
4. Download the usage statement for a selected month.
