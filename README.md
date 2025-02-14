# Even-or-Odd
Explanation:
import:
The import statement is used to bring in the Scanner class from the java.util package to read user input.
public class:
Defines a class named EVENODD. In Java, classes are used to structure code.


public static void main:
This is the entry point of the program where the execution starts. It’s a required method in any Java program.
Scanner:
Scanner is used to get user input from the console. In this case, it's used to read an integer.
System.out.print:
This is used to prompt the user to enter a number. It displays the message on the screen without moving to a new line.
nextInt():
The nextInt() method reads an integer value input by the user and stores it in the number variable.
if:
The if statement checks whether the number is even. It evaluates whether the condition number % 2 == 0 is true (i.e., the number is divisible by 2 with no remainder).
else:
If the condition in the if statement is false (i.e., the number is not divisible by 2), the else block is executed, indicating that the number is odd.
System.out.println:
This is used to display the result (whether the number is even or odd) on the screen.
scanner.close():
The close() method is called to close the Scanner object, releasing the resources it used.
