# LinkedListApplication-EmergencyRoom (C++)

A program to assist a hospital emergency room with serving patients. Patients waiting in an emergency room of a hospital are arranged on a waiting list based on the seriousness of their medical problems.  Each patient is evaluated and assigned a number 1 through 10 ranking the seriousness of their problem with 1 being most serious and 10 being least serious.  Let your program be menu driven using the following menu:

1.	Enter new patient
2.	Attend to most seriously ill patient
3.	Print waiting list
4.	Exit program

Use the following programming guidelines:
-	Use a linked list to implement the list of waiting patients.
-	Simulate the entering of a new patient (menu option 1) by allowing the user to input the patient’s first and last names, and then a ranking is assigned to the patient.  Simulate the assigning of the ranking by randomly generating a number from 1 to 10 (inclusive).  The patient is placed on the waiting list in the order of their ranking from most serious to least serious. Patients with the same ranking are placed on the list in the order that they enter the emergency room.
-	Simulate the attending to the most seriously ill patient (menu option 2) by removing the most serious patient from the linked list and print the name and ranking of the patient.  If option 2 is selected and no patients are on the list, print a message stating that there are no patients waiting.
-	Print the waiting list by printing the person’s name and rank in the order of most serious to least serious. Patients with the same ranking should be printed out in the order that they entered the emergency room.
-	The program ends when option 4 is selected from the menu.
