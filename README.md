# repo1
IDENTIFICATION DIVISION.
   PROGRAM-ID. MULTIPLY-NUMBERS.

   DATA DIVISION.
   WORKING-STORAGE SECTION.
   01 NUM1        PIC 9(5)V9(2).
   01 NUM2        PIC 9(5)V9(2).
   01 RESULT      PIC 9(10)V9(4).

   PROCEDURE DIVISION.
       DISPLAY "Enter the first number: " WITH NO ADVANCING.
       ACCEPT NUM1.
       DISPLAY "Enter the second number: " WITH NO ADVANCING.
       ACCEPT NUM2.

       COMPUTE RESULT = NUM1 * NUM2.

       DISPLAY "The product of " NUM1 " and " NUM2 " is " RESULT.

       STOP RUN.
