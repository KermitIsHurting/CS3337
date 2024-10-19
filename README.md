# CS3337
CSULA PARKING
Installation Instructions (I used Pycharm Pro but can work with other IDE's)

Clone the repository

Create a Virtual Environment

Terminal command: python3 -m venv venv

terminal command: source venv/bin/active

On windows use venv\Scripts\activate

Install the required packages:
terminal command: pip install -r requirements.txt

DataBase Installation Instructions (Mac)

Install PostgreSQL if you don't have it.
terminal command: brew install postgresql

Start PostgreSQL
terminal command: brew services start postgresql@14

Connect to PostgreSQL
terminal command: psql postgres

Create the database
terminal command: CREATE DATABASE csula_parking;

Create an .env file in the root directory
add this: DATABASE_URL=postgresql://username:password@localhost:5432/csula_parking
SECRET_KEY=your_secret_key

Replace 'username' and 'password' with your terminal username
and password, replace 'your_secret_key' with a random string or set of numbers
