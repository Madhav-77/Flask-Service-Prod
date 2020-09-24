# Flask-Service

Flask-Service is a Flask and Python based API service that will help our [ShopBridge(Angular app)](http://shopbridge.netlify.app/) to interact with MySql database.

Link to [Angular code](https://github.com/Madhav-77/ShopBridge)

## Installation

Make sure to have Python and pip installed on your system.

Check it by running this command.
```bash
pip --version
```
Download the code and store it in a directory.

Navigate to that directory and install the following packages by running these commands: 

```
pip install Flask
pip install Flask-Cors
pip install Flask-MySQL
pip install Flask-UUID
```

# Usage

Download and setup that goes with your system [Xampp](https://www.apachefriends.org/download.html).

#### Setup Database
- Download the .sql file
- Start the apache server and MySql from xampp controller 
- Go to your browser and enter localhost/ 
- Create database
- Import the .sql table file to your database 

#### Accessing the project
In browser, navigate to this [URL](HTTP://127.0.0.1:5200)

- HTTP://127.0.0.1:5200/ - Home route
- HTTP://127.0.0.1:5200/items - Get all the items
- HTTP://127.0.0.1:5200/item/id={id} - Get an item with particular id

## Link to project
[Flask-Service](https://services-flask-api.herokuapp.com/)
