# FIFA-World-Cup-DBMS-main
A DBMS project to store, manage, and query FIFA World Cup data, including teams, players, matches, and results. Features SQL queries, relationships, and reports for efficient data analysis.

📌 Overview
FIFA-World-Cup-DBMS is a relational database project designed to handle and organize detailed information about FIFA World Cup tournaments. It includes structured tables, relationships, and SQL queries to efficiently store and retrieve data such as teams, players, venues, match schedules, and results.

The project supports operations like:

Adding new teams, players, and matches

Updating player stats or match scores

Retrieving match history or team performance


Generating reports for tournament analysis

✨ Features
📊 Organized relational database design

⚡ Fast data retrieval using SQL queries

🔗 Proper relationships between entities (teams, players, matches, venues)

📜 Supports CRUD (Create, Read, Update, Delete) operations

🏆 Real-world FIFA World Cup dataset for learning and analysis


🛠️ Tech Stack
Database: MySQL / PostgreSQL (specify your DB)

Query Language: SQL

Tools: MySQL Workbench / phpMyAdmin / pgAdmin (depending on setup)


🚀 Installation & Setup
Clone the repository:


bash

Copy

Edit

git clone https://github.com/yourusername/FIFA-World-Cup-DBMS-main.git

cd FIFA-World-Cup-DBMS-main

Import the database schema:


Open your SQL client (MySQL Workbench, phpMyAdmin, etc.)


Import the .sql file from the project folder


Run queries from the queries.sql file to interact with the database.


📂 Usage Examples

Add a new match:


sql

Copy

Edit

INSERT INTO Matches (match_id, team1_id, team2_id, score1, score2, venue_id, date)  

VALUES (101, 1, 2, 3, 1, 5, '2022-12-18');

Get all matches played by a specific team:


sql

Copy

Edit

SELECT * FROM Matches WHERE team1_id = 1 OR team2_id = 1;

📌 Use Cases

Learning database design and SQL queries

Sports analytics and reporting

Building backend systems for sports applications
