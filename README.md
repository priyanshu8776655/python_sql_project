# Student Report Card Generator 

This project is built using *Python* and *MySQL*, which generates a student report card based on marks stored in a relational database.

##  Technologies Used
- Python 3.x
- MySQL (Relational Database)
- Pandas (for data processing)
- SQL (JOIN, GROUP BY, Aggregations)
##  Project Structure
- students table: Stores student ID and name
- marks table: Stores student marks in various subjects

##  What It Does
- Connects to a MySQL database
- Fetches data using real SQL queries (JOIN + GROUP BY)
- Calculates average marks
- Identifies whether a student is Pass or Fail
- Exports the final report to a CSV file

##  Sample Output (CSV)
| student_name | average_marks | result |
|--------------|----------------|--------|
| Priyanshu    | 87.67          | Pass   |
| Akash        | 35.00          | Fail   |
| Kanchan      | 65.00          | Pass   |

##  How to Run
1. Make sure MySQL is installed and running
2. Run the SQL script to create tables and insert sample data
3. Edit Python file with your DB credentials
4. Run the Python script

```bash
python student_report.py 
