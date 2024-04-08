# -SQL_Music_Store_Analysis_PROJECT

This SQL project involves analyzing a music store's database to derive insights about sales, customers, and products. The analysis will include querying the database to answer specific business questions and generate meaningful reports.

Dataset Description
The dataset used for this project includes several tables commonly found in a music store's database:

customers: Contains information about store customers (e.g., customer_id, name, email, city, country).

invoices: Includes details of customer transactions (e.g., invoice_id, customer_id, invoice_date, total).

invoice_items: Provides line-item details for each invoice (e.g., invoice_item_id, invoice_id, track_id, unit_price, quantity).

tracks: Describes individual music tracks available in the store (e.g., track_id, name, album_id, genre_id, composer, milliseconds, bytes, unit_price).

media_type: Contains information about different media types used for music tracks (e.g., media_type_id, name).

playlist: Describes playlists created by the store (e.g., playlist_id, name).

playlist_track: Links tracks to playlists, indicating which tracks are included in each playlist (e.g., playlist_id, track_id).

genre: Provides details about music genres (e.g., genre_id, name).

employee: Includes data about store employees (e.g., employee_id, first_name, last_name, title).

artist: Contains information about music artists (e.g., artist_id, name).

album: Describes music albums available in the store (e.g., album_id, title, artist_id).

invoice_line: Represents individual line items from customer invoices, showing which tracks were purchased (e.g., invoice_line_id, invoice_id, track_id, unit_price, quantity).
