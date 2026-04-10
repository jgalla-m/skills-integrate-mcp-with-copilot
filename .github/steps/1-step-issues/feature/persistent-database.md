# Feature: Persistent Database for Activities

## Description
Replace the current in-memory activity storage with a persistent database (e.g., SQLite, PostgreSQL, or MongoDB). This will ensure that activity data and signups are not lost when the server restarts.

## Acceptance Criteria
- Activities and participant data are stored in a database.
- Data persists across server restarts.
- The API and UI continue to function as before.

## Motivation
A persistent database is essential for real-world use and data reliability.