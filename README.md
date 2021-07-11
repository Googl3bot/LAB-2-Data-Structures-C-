# LAB-2-Data-Structures-C-
The purpose of this lab is to reinforce basic (and increasingly advanced) class concepts in C++. Lab 2 consists of the following problem specs: • Create a class for a program entity called: Process, with the following properties Member variables: o Process ID, which is an integer type o Priority number, which is an integer type o Process service time, which is a double type (random number) o Process waiting time, which is an integer type (random number) o Process arrival time, which is a double type (random number) and less than both the service time and waiting time. o Process completion order/position, which is an integer – a sequence: 1, 2, 3, …. N o Queue/List size, which is a ‘private’ integer type (random number) Member functions: o Enlist () // for adding a process ID to a ‘list’ or data structure o Delist () // for removing a process’s ID from a ‘list’ or data structure o Set_Priority () // for checking/getting the priority of a process for ‘scheduling’ o Waiting_Times () // for calculating/getting the time a process waits in a system o Time_In-System () // for calculating the total time a process stays in a system: service-time + waiting-time – arrival-time. (NOTE: the sum o Scheduler () // a function that acts as a scheduler selects a process and calls Time_In-System () based on the process’s priority number (the highest preferred over the lowest; ties are broken using first-come-first served criterion based on the arrival times). This function is the main driver that works on the Queue/List. o Statistician () // a function or method that computes the: average waiting time, average service time, and the average of time in the system. Add any member function/method you deem necessary to make your code work.
