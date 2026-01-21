<h1>
  <img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Education%20Database%20Query%20Tool.svg" alt="Education Database Query Tool"/><br>
</h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Overview.svg" alt="Overview" height="25px"/>

This project is a Python command-line application that uses SQLite to manage and query a structured academic database.  
It demonstrates practical database creation, SQL querying, and exporting query results in machine-readable formats.

The application allows users to retrieve student enrollments, course information, completion status, reviews, and address details through predefined commands.

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Key%20Functionality.svg" alt="Key Functionality" height="30px"/>

&#8287;&#8287;• Create and populate a relational SQLite database from a SQL script  
&#8287;&#8287;• Query courses taken by a specific student  
&#8287;&#8287;• Look up a student’s address by name  
&#8287;&#8287;• Retrieve course reviews for a student  
&#8287;&#8287;• List students who have not completed their courses  
&#8287;&#8287;• List students who completed courses with low marks  
&#8287;&#8287;• Export query results to JSON or XML

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Technologies.svg" alt="Technologies" height="30px"/>

&#8287;&#8287;• Python  
&#8287;&#8287;• SQLite  
&#8287;&#8287;• SQL  
&#8287;&#8287;• JSON  
&#8287;&#8287;• XML

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Project%20Files.svg" alt="Project Files" height="30px"/>

&#8287;&#8287;• `lookup.py` – application logic and user interaction  
&#8287;&#8287;• `create_database.sql` – database schema and seed data  
&#8287;&#8287;• Output files (`.json`, `.xml`) – generated from user queries

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Running%20the%20Application.svg" alt="Running the Application" height="30px"/>

1. Ensure Python is installed
2. Place all files in the same directory
3. Run lookup.py
4. Follow the on-screen prompts to execute queries

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Supported%20Commands.svg" alt="Supported Commands" height="30px"/>

&#8287;&#8287;**Student Information**  
&#8287;&#8287;&#8287;&#8287;• `vs <student_id>` – View subjects taken by a student  
&#8287;&#8287;&#8287;&#8287;• `la` – Lookup address for a student  
&#8287;&#8287;&#8287;&#8287;• `lr <student_id>` – List reviews for a student  

&#8287;&#8287;**Teacher & Courses**  
&#8287;&#8287;&#8287;&#8287;• `lc <teacher_id>` – List courses taught by a teacher  
&#8287;&#8287;&#8287;&#8287;• `lnc` – List students who haven't completed a course  
&#8287;&#8287;&#8287;&#8287;• `lf` – List students who completed a course with marks ≤ 30  

&#8287;&#8287;**System**  
&#8287;&#8287;&#8287;&#8287;• `e` – Exit the program  

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Data%20Export.svg" alt="Data Export" height="30px"/>

&#8287;&#8287;**After each query, results can optionally be saved as:**  
&#8287;&#8287;&#8287;&#8287;• JSON  
&#8287;&#8287;&#8287;&#8287;• XML


