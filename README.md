# Chinook Music Store — SQL Analysis

Exploratory analysis of a digital music store database using SQL (SQLite).  
The goal is to extract actionable business insights across sales, customers, catalog, and time trends.

## Database
The [Chinook database](https://github.com/lerocha/chinook-database) simulates a digital music store with tables for customers, invoices, tracks, albums, artists, and genres.

## Key Findings

**Sales & Revenue**
- USA is the top revenue-generating country ($523), followed by Canada ($303) and France ($195)
- Chile has the highest average order value ($6.66), suggesting fewer but larger purchases
- 2022 was the best performing year ($481), with a slight decline through 2025
- Q2 (April–June) is the strongest quarter ($592), January and June are the best individual months

**Customers**
- 14 out of 59 customers are classified as VIP (spent over $40)
- Helena Holý is the top customer with $49.62 in total spending
- The customer base spans 24 countries, with USA accounting for 22% of all customers

**Music Catalog**
- Rock dominates revenue at $7,720 — more than double the second genre (Latin at $3,472)
- Iron Maiden has the largest catalog with 213 tracks
- "Greatest Hits" is the biggest album with 57 tracks

## Skills Demonstrated
`SELECT` `WHERE` `GROUP BY` `HAVING` `JOIN` `LEFT JOIN` `Subqueries` `CASE` `AVG/MIN/MAX` `strftime()`
