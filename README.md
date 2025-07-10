🎵 Music Store SQL Analysis Project

📌 Relational Database Design & SQL Querying for a Digital Music Store

🧾 Overview:
     This project is a comprehensive SQL-based analysis of a digital music store's database. It includes the design, understanding, and querying of a normalized relational database that manages customer details,  music tracks, albums, artists, invoices, employees, and playlists.

  The project is ideal for practicing real-world SQL querying and database analysis skills using structured and meaningful business-related questions, ranging from basic SELECT statements to advanced CTEs and window functions.

🧩 Database Schema:

The music store database includes the following key tables:

Customer – Contains customer information including contact details and support rep ID.

Employee – Stores staff details and their reporting hierarchy.

Invoice & Invoice Line – Represents purchase transactions and their individual track details.

Track – Details of each music track including album, genre, media type, and pricing.

Album & Artist – Information about music albums and associated artists.

Playlist & Playlist Track – User-created playlists and associated tracks.

Genre & Media Type – Metadata tables defining track genres and formats.

Relationships between the tables are visualized using an ER diagram to help understand foreign key constraints and data flow.


🔍 Features & Query Categories:

The project is divided into three sets of SQL queries:

🔹 Question Set 1 – Easy

  Identify the senior-most employee by title

  Determine the countries with the most invoices

  Find the top 3 highest invoice totals

  Discover the most profitable city

  Identify the customer who spent the most

🔹 Question Set 2 – Moderate

   Find all customers who listen to Rock music
 
   Identify top 10 artists with the most Rock songs

   List tracks longer than the average song length

🔹 Question Set 3 – Advanced

   Calculate how much each customer spent on top artists

   Determine the most popular genre by country

   Identify top-spending customers by country


 🎯 These queries utilize:

  a. Joins (INNER, LEFT, etc.)

  b. Aggregation functions (SUM, COUNT, AVG)

  c. Subqueries

  d. Common Table Expressions (CTEs)

  e. Window Functions (ROW_NUMBER)


🛠️ Tools & Technologies Used:

   1. MySQL / SQL

  2. ER Diagram Tools (for schema visualization)

  3. DBMS Concepts – Normalization, Entity-Relationship Modelling

  4. SQL Techniques – Data aggregation, filtering, ranking, joins, CTEs


🚀 How It Works:

The database is created and populated with tables representing music-related entities.

SQL queries are written to analyze different aspects such as customer spending, artist performance, and regional sales trends.

Results from these queries provide valuable business insights that can inform marketing campaigns, artist promotions, and customer targeting strategies.
