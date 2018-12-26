# Grade-Book
When you execute the program, you must state how many students will be generated initially.

A menu will appear giving the user 5 options.

- The user enters 1 to add students to the grade book.
  The program will ask how many students the user wants to add.
  After entering a number, the program will state how many students were added and how many students there are in total.

- The user enters 2 to remove students from the grade book.
  The program will ask for the ID of the student that wants to be deleted.
  The program must state if the student has been deleted or no such student was   found.

- The user enters 3 to see the grade book.
  All of the students' names, ID's and grades will be printed to the console as in demo.
  All of grades' averages will also be printed (average of quiz1, average of midterm etc.).
    
- The user enters 4 to delete all students from the grade book.
    
- The user enters 5 to terminate the program.

<img src="https://github.com/alimhmdghanem/Grade-Book/blob/master/grade-book-demo.PNG?raw=true" alt="demo">

# Random student generator criteria:

Every student will have a first name, a last name, an ID, quiz 1, quiz 2, project, midterm and final grades, average and letter grade.

- First and last names will be generated randomly. First name's first letter will be upper case. Last name's all letters will be upper       case. Both names will have at least 3 and at most 8 letters.

- ID's will have 11 digits and will be unique for all students. They must be generated randomly.

- Quiz 1, quiz 2, project, midterm and final exams will have a random value between 0 and 100.

- Average will be calculated based on quiz 1, quiz 2, project, midterm and final grades. All grades have the same weight.

- Letter grade will be calculated based on average:
   
   If the average is between 0 and 30, the letter grade will be F.  
   If the average is between 30 and 50, the letter grade will be D.  
   If the average is between 50 and 60, the letter grade will be D+.  
   If the average is between 60 and 65, the letter grade will be C-.   
   If the average is between 65 and 70, the letter grade will be C.   
   If the average is between 70 and 75, the letter grade will be C+.   
   If the average is between 75 and 80, the letter grade will be B-.   
   If the average is between 80 and 85, the letter grade will be B.   
   If the average is between 85 and 90, the letter grade will be B+.   
   If the average is between 90 and 95, the letter grade will be A-.   
   If the average is between 95 and 100, the letter grade will be A.  

