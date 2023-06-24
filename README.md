# BrewingJava_TOURS-TRAVELS
Data Structures based project
## TOURS AND TRAVEL MANAGEMENT SYSTEM

Objective :-To develop Java program for tours and travels system that enables users to book tours and tickets for travelling by seeing availibility.
This system help travellers automate their booking, reservation and payment processes making it easier for users to enjoy their journey.
We have developed Tours and travel booking system I which we offer options of booking tours travels, and cancel the same.

Features :- 1. Login / Sign up
            2. Tour
            3. Travel
            4. Cancel tour
            5. Cancel travel
            
Data Structures :- 1) Queue 
                   2) Hashmap
                   3) Binary search tree (BST)

Algorithm : - Dijkstra's algorithm (Graph) 

DESCRIPTION:
1)Hash map is a data structure used to store key value pairs. In this project we have used hash map to store login and signup information of respective user. 
Each key value pair will represent a user’s login credentials with the key being the user name and the value being the password. When a user tries to login to the 
system the prog will check if the username and the password matches with the key-value pair in hash map if the combination is valid the user will be granted the 
access to the system. 

BST: bst is a tree based data structure in which each node has at most 2 children a left child and a right child. The left child node has a key value smaller than the
parent node and the right child node has key value greater than parent node. This property of bst enables efficient searching. In our project we have created a 
parent node of tour in which then we have created a array list of source and destinations  and under each source and destination we have created  bst of tour 
packages. So the searching we be if the user enters his/her required source and destination it will be connected to its respective bst of packages and when the user 
enters his desired package that amount will be searched in the respective bst if its available the user will be asked whether he wants to continue or if not he  will
be given an option that the package lesser than the amt he  desired for is available and do he wish to continue his booking with the same.

Queue : Queue is a data-structure that follows the first-in-first-out (FIFO) principle. In this project, we will use a Queue of booking classto store the booking 
requests made by the users. Whenever a user makes a booking request,  it will be added to the end of the queue. The booking requests in the Queue will be processed 
in the order they were received .Queue is used to check availability of seats during booking. If user want to cancel booking it will get removed from queue and we 
have created a temporary queue to store the entries other than the one that is to be deleted.

Dijkshtra algo: Dijkstra algo is used to find the shortest path between two nodes in a weighted graph.In this project we have used this algo to find the shortest
path from source to their respective travel destinations.

FUTURE SCOPE:
We are planning to make website for the same where we can also add real time payment api and can also use ai/ml to add features like customized suggestions and 
recommendation by using user’s history.It augmented Reality and Virtual Reality can be used to provide customers with the immersive travel eexperiences,
allowing them to virtually visit destinations before booking their trips.




