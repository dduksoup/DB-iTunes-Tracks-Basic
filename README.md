# DB-iTunes-Tracks-Basic

The original code for this program was provided 
by University of Michigan's online course
"Using Databases with Python" on Coursera.

The code is then modified to read XML data exported
from an iTunes library and store it into an
appropriately structured SQL database (SQLite3).

More specifically, the program:
- Parses the XML data
- Looks for 4 types of information related to the track
- Sets up SQL tables
- Loops through each track dict and stores relevant
  information in each table accordingly

At the end, one can do an SQL query that shows you a
list of tracks along with their artists, albums and genre.