# alx-airbnb-database

 SQL Joins Practice

This repository contains SQL queries demonstrating different types of joins for the Airbnb database.

## Queries

### 1. INNER JOIN
Retrieves only bookings that have matching user records in the users table. 
This excludes any bookings without users or users without bookings.

### 2. LEFT JOIN 
Retrieves all properties from the properties table, along with any matching reviews.
Properties without reviews will still appear in the results with NULL values for review columns.

### 3. FULL OUTER JOIN
Retrieves all records from both users and bookings tables, matching where possible.
This includes:
- Users with their bookings
- Bookings with their users
- Users without any bookings
- Bookings not linked to any user
