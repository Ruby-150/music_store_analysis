***🎵 Music Store Analytics Dashboard***

An interactive, multi-page business intelligence dashboard that turns a digital music store's sales data into clear, 
actionable insights on revenue, customers, geography, genres and artists.

📌 Problem Statement

A digital music store collects large volumes of transactional data (invoices, customers, tracks, genres, artists),
but this data is spread across multiple tables and is hard for business teams to interpret quickly. Stakeholders could not easily answer questions such as:

How much revenue is the store generating, and is it growing?

Which countries and cities contribute the most revenue?

Which genres and artists drive sales?

Who are the highest-value customers and invoices?

What does the catalogue look like (track count, average track length)?

Goal: Build a single, easy-to-use dashboard that gives executives a quick view of overall performance and lets analysts
filter and drill down by country, genre, artist and customer.

🧭 Approach

Data Collection & Understanding
Used the music store relational dataset (Customers, Invoices, Invoice Lines, Tracks, Genres, Albums, Artists).
Mapped table relationships and identified the key metrics to track.

Data Cleaning & Preparation
Handled missing values and duplicates, standardised country and city names, and fixed data types.
Joined tables to create a unified analytical model (invoice → customer → track → genre → artist).

Metric Definition (KPIs)
Total Revenue, Total Invoices, Total Customers, Total Tracks, Countries Served
Period-over-period change (% vs. last period) for each KPI
Average track length and revenue share by genre/country

Insight Generation
Added a Key Insights strip that highlights the top country, 
most popular genre, top artist, average track length and top listener.

📊 Results & Key Findings
Key insights

🌍 Top country: USA leads with $1,016.98 (≈13.7% of total revenue), followed by Canada ($535.59), Brazil ($427.05) and France ($395.44).

🏙️ Top cities: New York ($319.02), London ($280.47) and Berlin ($224.31) generate the highest revenue.

🎸 Top genre: Rock contributes 28.7% of revenue, followed by Pop (18.4%) and Metal (14.2%).

🎤 Top artist (Rock): The Rolling Stones, with 142 rock tracks in the catalogue.

🧾 Highest invoice: INV-00102 by Helena Berg at $39.62.

⏱️ Average track length: 4.32 minutes across 3,503 tracks; the longest track is The End at 9.42 minutes.

👑 Top customer: Luís Gonçalves (Customer ID 56).
