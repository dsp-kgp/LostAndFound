# lostfound
Campus Lost & Found Portal
Reuniting students with their belongings.

A centralized recovery portal designed for the campus community. This web application streamlines the process of reporting lost items and cataloging found objects. By leveraging fuzzy string matching, the system proactively suggests matches, reducing the manual effort required to connect finders with owners.

Key Features

Smart Similarity Matching
Gone are the days of scrolling through endless lists. We use RapidFuzz to analyze item descriptions and names.
How it works: If a student reports a lost "Blue Dell XPS," and someone finds a "Dell Laptop Blue," the system detects the high similarity and alerts the user automatically.

Instant Notifications
Real-time Alerts: Built with AJAX, users receive notifications about potential matches or status updates without needing to refresh the page.
Interactive UI: Clean Bootstrap modals provide quick views of item details.

Campus-Centric Design
Secure Authentication: User accounts to ensure accountability.
Status Tracking: Items are marked as Lost, Found, or Returned to keep the database clean.

Tech Stack

Backend: Django 5.2

Database: PostgreSQL (via psycopg2-binary)

Frontend: Bootstrap, AJAX, jQuery

Other Libraries: RapidFuzz (matching), Pillow (images), Widget Tweaks

Deployed link to the website - https://lostandfound-umber.vercel.app/
Have a look and feel free to use  
