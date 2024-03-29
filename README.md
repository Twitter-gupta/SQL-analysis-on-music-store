# SQL-analysis-on-music-store
In this project i have been quering on different tables that is a star flake schema .
Number of tables and columns-
album - album_id , title , artist_id
artist - artist_id, name
customer - customer_id, first_name, last_name, company, company,city,    state, country, postal_code, phone, fax, email, support_rep_id
Employee- employee_id,last_name	,first_name, title, reports_to, levels, birthdate, hire_date, address, city, state, country, postal_code,phone, fax,email
genre- genre_id, name
invoice- invoice_id, customer_id, invoice_date	,billing_address, billing_city, billing_state, billing_country, billing_postal_code, total
invoice_line - invoice_line_id,	invoice_id,track_id,unit_price,quantity
media_type- media_type_id, name
playlist- playlist_id, name
playlist_track - playlist_id, track_id
track- track_id	name, album_id, media_type_id, genre_id,composer, milliseconds, bytes, unit_price

Analysed data using queries on several tables ,created table schema under lucid.app to have better understanding of relationship between tables .Used joins to join tables to another and grouping them .

Tables schema
<img width="505" alt="star flake" src="https://github.com/Twitter-gupta/SQL-analysis-on-music-store/assets/164379382/3e563d4c-9344-4907-8946-d1e4b8bba39d">


1. Who is the senior most employee based on job title?
   <img width="715" alt="senior most employee based on job title" src="https://github.com/Twitter-gupta/SQL-analysis-on-music-store/assets/164379382/1ff862ff-13db-41f2-be9e-8a103848ac73">


2. which countries have the most invoices?
<img width="269" alt="country- USA having the most invoices" src="https://github.com/Twitter-gupta/SQL-analysis-on-music-store/assets/164379382/c86c0877-d292-4cae-b10e-a9fcfb021439">


3. what are top values of total invoice?
<img width="733" alt="top values of total invoice" src="https://github.com/Twitter-gupta/SQL-analysis-on-music-store/assets/164379382/4add78fd-4ce5-42a4-91a1-fd9ed2e5b7ab">


4. which city has best customer?
  <img width="374" alt="prague city has best customer" src="https://github.com/Twitter-gupta/SQL-analysis-on-music-store/assets/164379382/5a29714b-950e-48be-9c06-d79133393ebe">


5. who is the customer_id made highest number of invoices ?
   
   <img width="361" alt="customer_id made highest number of invoices" src="https://github.com/Twitter-gupta/SQL-analysis-on-music-store/assets/164379382/d3e469f0-3d2a-4784-9229-0e8470e2c793">


7. Write query to return the email , first name, last name and genre of all rock music listeners .Return your list ordered alphabetically by email starting with A.
   <img width="375" alt="email , first name, last name and genre of all rock music" src="https://github.com/Twitter-gupta/SQL-analysis-on-music-store/assets/164379382/ae034fa5-436b-4d14-a7ba-f069aa5b7cd8">


8. Let's invite the artist_ids who have written the most rock music in our dataset. 
A query that returns the Artist id and total track count of the top  rock bands.
<img width="335" alt="artist_id who have written the most rock music" src="https://github.com/Twitter-gupta/SQL-analysis-on-music-store/assets/164379382/0aee27c1-552a-4dc1-9c83-1e3811582ea6">


9.  Return all the track names that have a song length longer than the average song length. 
Return the Name and Milliseconds for each track. Order by the song length with the longest songs listed first.
<img width="335" alt="song length longer than the average song length" src="https://github.com/Twitter-gupta/SQL-analysis-on-music-store/assets/164379382/25bc5fac-4167-4e04-ac6d-16cc48ec0446">


