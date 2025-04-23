# Final Lab Task 2 - Transforming ER Model to Relational Tables

## Student Table:
- **username**: String (VARCHAR),up to 50 characters.
## Assignment Table:
- **shortname**: String (VARCHAR),up to 50 characters.
- **due_date**: Date, cannot be null.
- **url**: String (VARCHAR),up to 255 characters, can be null.
## Submission Table:
- **username**: String (VARCHAR),up to 50 characters.
- **shortname**: String (VARCHAR),up to 50 characters.
- **version**: Integer, represents the version of the submission.
- **submit_date**: Date, cannot be null.
- **data**: Text.
## Query Statements & Table Structure:
### Student:
#### Query:
![screenshot](Image/Screenshot%202025-04-23%20214006.png)
#### Table:
![screenshot](Image/Screenshot%202025-04-23%20214011.png)
### Assignment:
#### Query:
![screenshot](Image/Screenshot%202025-04-23%20214017.png)
#### Table:
![screenshot](Image/Screenshot%202025-04-23%20214022.png)
### Submission:
#### Query:
![screenshot](Image/Screenshot%202025-04-23%20214029.png)
#### Table:
![screenshot](Image/Screenshot%202025-04-23%20214533.png)
## ER Diagram:
![screenshot](Image/Screenshot%202025-04-23%20214040.png)
