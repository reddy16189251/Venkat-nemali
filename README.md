2.Explain the boundary conditions of the implemented code.
*As per question we are bounded to take the number of readers has now increased by 1: readcnt++;
*Reader wants to enter the critical section: wait(mutex);
*There is atleast onr reader in the critical section.
*Other readers can enter while this current reader is inside.

3.Explain all the test cases applied on the solution of assigned problem.
     Test Case 1:
     When the user Enter Number of “WRITER” is Negative.
No WRITER and READER thread will be Created.
No read or write operation done.
Program will be terminated.
Test Case 2:
When the user Enter Number of “READER” is Negtive.
No WRITER and READER thread will be created.
No read and write operation done.
Program eill be terminated.
Test Case 3:
      When Number of “WRITER=0” is taken as input
Only READER thread will be created.
No WRITER thread is created.
No updating of the shared variable.
Test Case 4:
     When Number of “READER=0” is taken as input.
Only WRITER thread is created.
No READER thread is created.
No reading of the shared variable.
Test case 5:
     User taken same number of READER and      WRITER ie  READER=WRITER.
 Both READER and WRITER threads created .
Any WRITER can update the shared variable any number of times
Any READER can read that value any number of times.
