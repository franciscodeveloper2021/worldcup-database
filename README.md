# World Cup Database Project

This project consists of scripts and a PostgreSQL database dump related to the FIFA World Cup.

## Overview

The project includes the following files:

- `worldcup.sql`: PostgreSQL database dump containing schema and sample data.
- `import_data.sh`: Bash script to import data from a CSV file into the PostgreSQL database.
- `queries.sh`: Bash script to execute SQL queries against the database.
- `README.md`: This file, providing an overview of the project.

## Setup

To set up the project, follow these steps:

1. **Database Setup**: Ensure PostgreSQL is installed on your system.
2. **Import Data**: Run `insert_data.sh` to import data from a CSV file into the database.
3. **Run Queries**: Execute `queries.sh` to perform various queries against the database.

## Files

### `worldcup.sql`

This file contains the PostgreSQL database dump. It includes schema definition and sample data for tables `games` and `teams`.

### `insert_data.sh`

This Bash script is used to import data from a CSV file into the PostgreSQL database. It reads data from `games.csv` and populates the `games` and `teams` tables accordingly. The script allows for testing without affecting the original database.

### `queries.sh`

This Bash script executes various SQL queries against the PostgreSQL database. It provides insights into the data, such as total goals, average goals, team information, and more.

## Usage

- Run `insert_data.sh` to import data into the database.
- Execute `queries.sh` to perform SQL queries.

## Dependencies

- PostgreSQL
- Bash

## Note

- Ensure proper permissions are set for executing the Bash scripts (`insert_data.sh` and `queries.sh`).

