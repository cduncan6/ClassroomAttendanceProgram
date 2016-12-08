# ClassroomAttendanceProgram
Code repository for the Classroom Attendance Program by Cody Duncan, Mario Esho, Bryan Fillion, Charles Miller, Stephen Murphy, and Jeffery Wang for University of Toledo Capstone Project. 

To download the Xampp program used to setup the server, go to the following link(We do not own Xampp, it is a free product and all licenses and trademarks are the property of Apache Friends.)


https://www.apachefriends.org/download.html


The zip file called ServerandWebsite contains the following files:


      1) ClassroomAttendanceProgram zip file. This contains the Classroom Attendance Program web files. After installing the program XAMPP, place the folder in the location C:\Xampp\htdocs\. This site is located via http://Localhost/ClassroomAttendanceProgram. 
      
      
      2) .htaccess file. This allows html to use PHP in its files. Must be placed in the following folder:
      
      
              C:\Xampp\htdocs
              
              
      3) Test data, including an Expo_Test.sql and two files for import. Teststudent.csv contains test student names and rocket numbers,
      
      and TestAttendance.csv contains test data taken from the physical unit. 
      
       4) Recreatealltables.doc, a sql file that creates all tables required for the website to function. To import these files, please use the following link. 
       http://localhost/phpmyadmin/
       
       
       5) The tutorial for the website, also is on the website itself. 


The zip file called CAPpiFiles.zip contains the following files:
      
      
      1)CAPupload.py, which contains the upload to the server script. 
      
      
      2)CAPmain.py, which contains the main file used by the pi to recieve swipe data. 
