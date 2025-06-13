# CSCI-4000-Assignment-4-solution

Download Here: [CSCI 4000 Assignment 4 solution](https://jarviscodinghub.com/assignment/csci-4000-assignment-4-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Question 1 – Database: PHP Chapter 4, eg009 and knowledge of SQL (20 points) Estimated time: 3 hours
• Save question 1 files in folder “lastname_firstname_assignment4”: (2 points)
o create_db.sql
• Create a text file create_db.sql, write sql statements in the file to
o Create a MySQL database richard_ricardo_student_db. (2 points)
o In the database, create 2 tables. (2 points)
 major
 student

o Create the following fields (columns) for the tables (refer to examples below for details).
 major table: majorID, majorName (2 points)
 student table: studentID, majorID, firstName, lastName, gender (2 points)
o Do foreign key referencing, to maintain referential integrity (3 points)
 One student can only have one major.
 One major can be used (enrolled) by many students.
 majorID is the primary key of the major table.
 studentID is the primary key of the student table.
 majorID is a foreign key of the student table, for any values of majorID appearing in the
student table, these values must also appear in the major table.
o Insert test records to major table and student table. (3 points)
o Create a MySQL database username richardricardo1 with password richardisgreat, with data
privileges (select, insert, update, delete) for the richard_ricardo_student_db database. (4 points)
o All above must be done by SQL statements in the text file create_db.sql. (0 points if not)
• Load create_db.sql in XAMPP > phpMyAdmin to create the above mentioned database.
• Note: In the real world, do NOT put sql files in a website folder. Keep it offline and safe.

Question 2 – Display: PHP Chapter 4, eg009 and knowledge of SQL (35 points) Estimated time: 4 hours • Save question 2 files in “lastname_firstname_assignment4”: (4 points) o index.php o main.css o richard_ricardo_database.php o richard_ricardo_database_error.php • Create web page(s) that displays the default information (example shown). • The initial page and related outputs should look like the examples shown below. • Create your page(s) using “richard ricardo’s kung fu school” as the page title(s) (

• Create file richard_ricardo_database.php (php code only, no html code) to connect to database
o Use PDO (PHP Data Object) to interface with your MySQL database.
o Connect to the richard_ricardo_student_db MySQL database (created in Q1), using username
richardricardo1 with password richardisgreat.
o Use try {} catch () {} exception handling to detect if the connection is successful.
o If the connection is not successful, show an error page richard_ricardo_database_error.php.
• Create a css file named main.css to format all pages by creating your own layout (no two students should
have the same layout). You should use the same css file to format all questions. (6 points)
• index.php
o Uses richard_ricardo_database.php to connect to the database.
o The sidebar on the left displays a list of majors from the “major” table (created in Q1).
o The main portion of the page lists the students from the “student” table (created in Q1), for that
major.
o If a user wants to view the students in another major, the user can click on the link for tha

Question 3 – Delete Student: PHP Chapter 4, eg009 and SQL (20 points) Estimated time: 3 hours • Save question 3 files in folder “lastname_firstname_assignment4”. (2 points) o richard_ricardo_delete_student.php • The initial page and related outputs should look like the examples shown below. • Create your page(s) using “richard ricardo’s kung fu school” as the page title(s) (

Question 4 – Add Student: PHP Chapter 4, eg009 and SQL (25 points) Estimated time: 4 hours • Save question 4 files in folder “lastname_firstname_assignment4”. (2 points) o richard_ricardo_add_student_form.php o richard_ricardo_add_student.php o richard_ricardo_error.php • The initial page and related outputs should look like the examples shown below. • Create your page(s) using “richard ricardo’s kung fu school” as the page title(s) (

Question 5 Extra Credit – List / Add Major: (20 points) Estimated time: 4 hours • Save question 5 files in folder “lastname_firstname_assignment4”. (1 point) o richard_ricardo_major_list.php o richard_ricardo_delete_major.php o richard_ricardo_add_major.php • The initial page and related outputs should look like the examples shown below. • Create your page(s) using “richard ricardo’s kung fu school” as the page title(s) (

Important: 1. If you do not put / in the above mentioned fields (as shown in the examples), you will get 0 points for the question(s). 2. No two students should submit webpages with exactly the same code, content, layout, or color combination. If found, both students will get 0 points. 15 CSCI 4000 3. Before adding PHP code, all html files must pass html validation at https://validator.w3.org/ without any error (and with only 1 warning). Use the validator’s “File Upload” tab to check each file. a. If you want to validate a PHP file after adding PHP code, you can temporarily rename the *.php file to *.htm file. b. When you view page source in a web browser, must be at the top of every page. In other words, all pages must be written in HTML5. (-20 points if not) c. If any html error is found, 2 points will be deducted for each error. Please validate the files before adding PHP code. 4. All css files must pass css validation at https://jigsaw.w3.org/css-validator/ without any error. 5. If your files do not pass the html and css validations, 2 points will be deducted for each html or css error found (no deduction for php error at html validation). 6. Document (comment) your HTML files (), CSS files (/* */), and PHP files (/* */ OR //). Points will be taken off for insufficient comments (, /* */, //). Submission instructions: • You need to test all document(s). • Do screen capture(s) of the input and the related output(s). Use any graphic editing software (e.g. Microsoft Paint, Adobe Fireworks, GIMP, or Microsoft Expression Design etc) to cut out the browser output (from the screen capture), paste them into a word document. • Provide 2 different test cases for each question. In other words, for each question, you may need to have 2 input screen captures and 2 related output screen captures. • Do NOT need to do screen capture(s) of html validation results and css validation results for this assignment. • Save the word document as a pdf file. You need to submit the following: 1. A pdf file containing the screen capture(s) of the web browser input and output pages, name the file lastname_firstname_assignment4.pdf. 2. All html file(s), php file(s), css file(s), and other related files (e.g. image files). Zip your file folder (lastname_firstname_assignment4) into a single zip file (or rar file) lastname_firstname_assignment4.zip. In the above example, the zip file should contain the following files and subfolders. If there is any image, there should be a \images\ subfolder. • lastname_firstname_assignment4\create_db.sql • lastname_firstname_assignment4\index.php • lastname_firstname_assignment4\main.css • lastname_firstname_assignment4\richard_ricardo_add_major.php (extra credit) • lastname_firstname_assignment4\richard_ricardo_add_student.php • lastname_firstname_assignment4\richard_ricardo_add_student_form.php • lastname_firstname_assignment4\richard_ricardo_database.php • lastname_firstname_assignment4\richard_ricardo_database_error.php • lastname_firstname_assignment4\richard_ricardo_delete_major.php (extra credit) • lastname_firstname_assignment4\richard_ricardo_delete_student.php • lastname_firstname_assignment4\richard_ricardo_error.php • lastname_firstname_assignment4\richard_ricardo_major_list.php (extra credit) Please submit the above mentioned two files (.pdf and .zip) to D2L digital dropbox. Grading guidelines (programming questions): Your programs will be judged on several criteria, which are shown below

