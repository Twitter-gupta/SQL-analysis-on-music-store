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


Tables schema
"C:\Users\Divya\OneDrive\Documents\Music_store data\screenshot\star flake.png"

1. Who is the senior most employee based on job title?
   "C:\Users\Divya\OneDrive\Documents\Music_store data\screenshot\senior most employee based on job title.png"

2. which countries have the most invoices?
"C:\Users\Divya\OneDrive\Documents\Music_store data\screenshot\country- USA having the most invoices.png"

3. what are top values of total invoice?
"C:\Users\Divya\OneDrive\Documents\Music_store data\screenshot\top values of total invoice.png"

4. which city has best customer?
   "C:\Users\Divya\OneDrive\Documents\Music_store data\screenshot\prague city has best customer.png"

5. who is the customer_id made highest number of invoices ?
   "C:\Users\Divya\OneDrive\Documents\Music_store data\screenshot\customer_id made highest number of invoices.png"

6. Write query to return the email , first name, last name and genre of all rock music listeners .Return your list ordered alphabetically by email starting with A.
   "C:\Users\Divya\OneDrive\Documents\Music_store data\screenshot\email , first name, last name and genre of all rock music.png"

7. Let's invite the artist_ids who have written the most rock music in our dataset. 
A query that returns the Artist id and total track count of the top  rock bands.
"C:\Users\Divya\OneDrive\Documents\Music_store data\screenshot\artist_id who have written the most rock music.png"

8.  Return all the track names that have a song length longer than the average song length. 
Return the Name and Milliseconds for each track. Order by the song length with the longest songs listed first.
"C:\Users\Divya\OneDrive\Documents\Music_store data\screenshot\song length longer than the average song length.png"


