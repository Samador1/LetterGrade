# LetterGrade
/* A program to translate a numeric grade into a letter grade Amador, Sierra */

import java.util.Scanner;

/** *

@author sierraamador */ public class LetterGrade { public static void main( String [] args) { Scanner scan = new Scanner ( System.in); String LetterGrade = new String ("The grade is");

System.out.print(" Enter your test grade ");
int grade = scan.nextInt(); System.out.print( "Enter your grade as an integer > "); while (! scan.hasNextInt());

if (grade >= 97) //Code for A+ System.out.println("letter grade = A+ ");

else if (grade >= 93) //Code for A System.out.println("letter grade = A ");

else if (grade >= 90) //Code for A- System.out.println("letter grade = A- ");

else if (grade >= 87) //Code for B+ System.out.println("letter grade = B+ ");

else if (grade >=83) //Code for B System.out.println("letter grade = B");

else if (grade >=80) //Code for B- System.out.println("letter grade = B- ");

else if (grade >=77) //Code for C+ System.out.println("letter grade = C+");

else if (grade <=73) //Code for C System.out.println("letter grade = C");

else if (grade <=70) //Code for C- System.out.println("letter grade = C- ");

else if (grade <=67) //Code for D+ System.out.println("letter grade = D+ ");

else if (grade <=65) //Code for D System.out.println("letter grade = D ");

else if (grade <=60) //Code for D System.out.println("letter grade = D- ");

else if (grade <=59) //Code for F System.out.println("letter grade = F");

} }
