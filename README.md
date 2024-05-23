# ECommerce


## Description
- The back-end of an ecommerce website utilizing mySQL2, sequelize, dotenv, express
- A database can be created updated and deleted
- Tables can be added, updated, and deleted via modules

## Table of Contents

<<INSTALLATION>>
<<USAGE>>
<<CREDITS>>
<<LICENSE>>

## Installation

- bash''''
  - npm init
  - npm install mysql2
  - npm install dotenv
  - npm install seqeulize
  - npm install express


## Usage

- Create a database first by 

'''bash'''
mysql -u root -p

- enter password as prompted 
- in mySQL shell 

'''bash'''
DROP DATABASE IF EXISTS ecommerce_db
CREATE DATABASE ecommerce_db

- exit mySQL shell by entering 'quit'
- in the terminal

'''bash'''
npm run seed

- This will seed the database with data
- In the terminal

'''bash'''
npm start

- The server can be accessed with INSOMNIA
## Credits

Abhudaya Rayamajhi

https://github.com/abhuraya/ECommerce
https://abhuraya.github.io/ECommerce/
<video controls src="video/ECommerce Walkthrough Part 1.mp4" title="ECommerce Video Part 1"></video> 
<video controls src="video/ECommerce Walkthrough Part 2.mp4" title="ECommerce Video Part 2"></video>
## License

Mozilla License
