# AirplaneSeating
The AirplaneSeating program asks the user for the seat they would like to reserve.
  A layout of the plane is printed and an X is placed in the reserved seat.  The 
  program finds if the seat is available and if the entry is valid.  A sentinel of q
  ends the program.
 
  @author Quang Pham
  @version Module8, Lab 2, 4/1/20
  
     Algorithm:
     
     1. Greet user and ask which seat they would like to reserve.
     2. Print a layout of the plane and the seats available. 
     3. Put an X in the position where the user would like to reserve.
     4. Loop and ask if they'd like to reserve another seat.
     5. Make certain seat is available and the entry is valid, if sentinel q
        is entered, exit program.
     
     Problem Description:
     
     Write a program to assign passenger's seats in a small airplane.  Assume the 
     plane has its seats numbered as follows:
 
    Row
     1   A B  C D  
     2   A B  C D
     3   A B  C D
     4   A B  C D
     5   A B  C D
     6   A B  C D
     7   A B  C D
 
           You should verify that the user enters rows between 1 and 7 only, and
      columns A, B, C, or D only.  If the user enters an entry that is invalid,
      print an error message telling them what's wrong, then prompt for the next
      entry.  Model the seats in the plane using a multi-dimensional array with
      seven rows and four columns.  Use a loop in your program which continues to
      prompt for a seat to reserve until either the user specifies a sentinel to
      stop the program, or when all seats are reserved.
         After each entry from the user, the program should display the seat
      reservation pattern, with an 'X' marking the seats already assigned. For 
      example, after seats 1A, 2B, and 4C are reserved, the display might show 
      the following:
 
   Row
     1   X B  C D
     2   A X  C D
     3   A B  C D
     4   A B  X D
     5   A B  C D
     6   A B  C D
     7   A B  C D
 
        There are 25 seats available.  This continues until either all seats are
  filled or the user enters a sentinel indicating that he/she is done entering
   reservations.  If the user tries to reserve a seat which is already taken, the
  program should say that that seat is occupied and ask for another choice.
        Submit program files for all classes, as well as a print screen or screen
   snip showing what your screen looks like after 4 or 5 seats have been assigned.
   Be sure to demonstrate what happens when the user tries to reserve a seat that
   is already taken or specifies an invalid seat (for example, 9A or 5E).
 
