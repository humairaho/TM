# TM

This program can only be executed through Command Prompt (cmd) due to the lack of time to develop the rest service and server.
However, this program still is executable to obtain the desired results.

User will be able to find the results in the MySql Database called TM, table name is assignment_result.

First of all,

In order to run this program, user need to have the following requirements in their local machine which is:

1. Xampp must be installed in user local machine for database purpose.
2. Import the tm.sql file into mysql database using Xampp.
2. JDK 1.8.0_191 must be installed in user local machine.
3. csv files copied to C drive path. (Example: C:\csv_files)
4. copy the mysql-connector.jar to the installed Java folder located in Program Files. (Example: C:\Program Files\Java\jdk1.8.0_191\jre\lib\ext)
5. Log file must be created in the following path: 
    a) C:\TM_Log\MyLogFile.log

Steps to execute the program are as follow:

1. Download the executable java program and put the program to where it is convenient to execute later. (Example: C:\Users\humairah\Desktop\PERSONAL\TM\Task)
2. Download the csv_files.zip file to C path. (Example: C:\csv_files)
3. Make sure that the zip file is extracted before run the java program. (Example: C:\csv_files)
4. Once above step is completed, kind open the Command Prompt as Administrator. Go to the path where executale java program is located. (Example: C:\Users\humairah\Desktop\PERSONAL\TM\Task)
"Command: cd C:\Users\humairah\Desktop\PERSONAL\TM\Task"
5. Execute the following command to perform the java program.
"Command: java -cp tasks-0.0.1-SNAPSHOT.jar tasks.Task_Team"
6. For user to view the log, user may find the log file in the following path:
    a) C:\TM_Log\MyLogFile.log
