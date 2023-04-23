Download Link: https://assignmentchef.com/product/solved-605-201-introduction-to-programming-using-java-assignment-11
<br>
Write a program that uses one of the Map classes to implement a contact list. Contact information should include first name, last name, company name, phone number and an email address. You can assume a combination of first and last name are unique.  The list should be stored on your computer’s file system. The program should prompt the user for the name of the file where the information is stored, and allow the user to add a contact from the list, delete a contact from the list, and display the entire contact list (all fields) in a reasonable readable format in last name and with the same last name first name order.  This program counts 70% of the Correctness grade.

A print queue is a list of documents, called jobs, waiting to be printed. Each job is assigned an integer job number and an estimated print time, in seconds. If a job arrives and the printer is currently printing another job, the job waits in the print queue. This type of waiting line is called a first-in-first-out (FIFO) or first-come-first-serve (FCFS) waiting line model or queue. The Java LinkedList class is a pretty good class for implementing a waiting line model like this in code.

Write a program that uses a LinkedList object to store a list of print jobs in a FIFO queue. We will assume that each job has a unique job number that is assigned sequentially, and that the print time is randomly distributed between 10 seconds and 1000 seconds. These two data elements should be defined as part of a Job class. The program should prompt the user to either add a job to the queue or to quit. When a user adds a job, the program assigns a job number and randomly generates a print time for the job. When the user quits, the program will display the jobs (i.e., the job id and print time) in the queue, in the order in which they were added.

For this exercise, you can use the java.util.Random class to generate random numbers, as follows:

Random rnGenerator = new Random( rnSeed ); // creates a Random object printTime = rnGenerator.nextInt(991) + 10; // next int in range 10-1000

The first statement above instantiates a Random object called rnGenerator. The constructor argument rnSeed is called a random number seed. It is of type long, and is used to help ensure that the same sequence of random numbers is generated each time the program is run…which is helpful for test purposes. The nextInt() method returns a random integer in the range 0 to 999.

This program counts 30% of the Correctness grade.

Submit the source code and  screen shots of each program’s output in a zip file named as follows: Assignment11 followed by an underscore (_) followed by your first name initial, followed by your last name, followed by your course section number. For example, if your name is Jane Smith and you are in section 81 your zip file would be <em>Assignment11_jsmith81.zip</em>.