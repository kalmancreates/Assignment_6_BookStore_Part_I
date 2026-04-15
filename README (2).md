# Homework 1 — Bookstore Database + Python CLI

**Author:** Kalman

## Description

A music bookstore database built with SQLite and a Python command-line interface for browsing and managing books. The store carries biographies, learn-to-play guides, music theory texts, and scores/collections.

## Files

- `createTables.sql` — creates the `category` and `book` tables
- `insertRows.sql` — inserts 4 categories and 13 books
- `bookstore.db` — the SQLite database file
- `bookstore_cli.py` — Python CLI for interacting with the database

## Create the Database

```bash
sqlite3 bookstore.db < createTables.sql
sqlite3 bookstore.db < insertRows.sql
```

## Run the Python CLI

```bash
python3 bookstore_cli.py
```

## Additional Feature

**Search books by author** — option 5 in the menu lets you search for books by entering an author keyword.
