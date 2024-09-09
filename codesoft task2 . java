import java.util.Scanner;

public class Grade {
    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter the number of subjects: ");
        int num = sc.nextInt();
        int tot = 0;
        int[] marks = new int[num];

        for (int i = 0; i < num; i++) {
            System.out.println("Enter marks for Subject " + (i+1)  + ": ");
            marks[i] = sc.nextInt();
            tot += marks[i];
        }

        double avgPer = (double) tot / num;

        System.out.println("\nTotal Marks: " + tot);
        System.out.println("Average Percentage: " + avgPer + "%");

        char grade = calculateGrade(avgPer);
        System.out.println("Grade: " + grade);

        
        sc.close();
    }

    
    private static char calculateGrade(double avgPer) {
        if (avgPer >= 90) {
            return 'A';
        } else if (avgPer >= 80) {
            return 'B';
        } else if (avgPer >= 70) {
            return 'C';
        } else if (avgPer >= 60) {
            return 'D';
	}
	else if (avgPer >= 50) {
            return 'E';
        } else {
            return 'F';
        }
    }
}