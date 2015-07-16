# fullstack-nanodegree-tournament-results
Full Stack Web Developer Nanodegree - Project 2: Tournament results

The repository contains the files corresponding to project 2: tournament result

- tournament.sql: script file containing sql commands for creating the tournament database and its tables and views
- tournament.py: python methods that access the previous database
- tournament_test.py: code for testing the methods in the tournament module. This file has been extended from its 
original state, to include a test for the OMW functionality (extra credit)

All files include proper documentation explaining their details.

## Implementation

The code implements all basic requirements in the project, plus the OMW functionality from the extra credits

The extra functionality is tested using code shared by a student in the forums: https://discussions.udacity.com/t/test-cases-for-project-2-extra-credit/18699

## Database structure
This script file contains the sql commands to create the schema of the tournament database. The database is composed of two tables: 'players' and 'matches'. The former stores information about the registered players, and the latter about already finished matches between players.

The file also includes the definition of four views for facilitating the retrieval of data in the python application.

## Testing

- Step 1: setup the tournament database by running the tournament.sql scripts in psql. This creates the database and its schema, including views
- Step 2: run tournament_test.py in Python (2.7.9)

