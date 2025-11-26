#Qn 1
##File - Is a collection of data or information stored in a computer's disk or storage device permanently under single name.
##File mode - Is a setting you specify when opening a file that tells the computer what you intend to do with the file. example saying am opening it to read it.
##Text file - Is a file where data is stored in readable text characters like letters and numbers which makes it easy to read and open with basic text editor.
##Binary file - Is a file where data is stored in machine readable binary format and its meant for computers to read it directly. eg image file (.jpg).
##File handling - Is the process of performing operations on files. eg opening and reading.

#Qn 2
-File handling in programming is needed mainly to store data permanently so that you can be able to come and re use it again also be able to share the data between different programs.

#Qn 3
##3(a) 'w'(write mode) we use it to write data in a file but if the file already existed this mode will DELETE all the existing data and start write from blank, also if the file didn't exist then it will create a new one. 
WHILE 
'a' (append mode) we use it to add data to  file, it preserves the exixting data and start writing at the end of the file, also if the file didn't exist it created a new one.
##3(b) Text file it stores data as a sequence of characters that a computer provide translation a human can read WHILE Binary file its stores data in a special code that only the computer can understand and no translation here 
also its used to store data like images or audio files.

#Qn 4
- When you open a file using 'r'(read) mode is like telling the computer that i only want to read the contents and won't change or edit anything on the file, if the file is not found then it will give an error beacuse it cant find anything for you to read.

#Qn 6 
##(a) The main problem is the lack of data persistance since the data is stored  temporary in RAM where by it will be completely erased when the program terminates.
##(b) File handling solves this by allowing the program to write the data from  memory to the hard disk, which will store data permenently and then it can read the data back when the program runs again.

#Qn 8
##(a) The program must use the 'a' mode to store the scores.
##(b) If the program uses the 'w' mode everytime new student score record is entered then it will delete the existing ones that leads to lose of students data but when the program uses
 'a' mode it will allow the user to add new records without deleting the previous ones at the end of the file this helps to store all the students data and record and allows the use to edit anytime needed while storing other record,
