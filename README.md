Printing Numbered Square Pattern
In this program we’re going to code a Java Program for printing number square star pattern.

The logic of this problem is to take a row and column input from user and store in the variable names as row and col and then take a for loop start from int i=1 i<=row and then take inner for loop start from j=1 to j<= col and then print 1 and then change the line

Java Program for Numbered Square Pattern
Algorithm:
Take number of rows/columns as input from the user and save it in any variable (‘row’ and ‘col’ in this case).
Run a loop ‘row’ number of times to iterate through the rows. From i=1 to i<=r.  The loop should be structured as for(int i=1 ; i<=row ; i++)
Run a nested loop inside the previous loop to iterate through the columns. From  j=1 to j<=col. The loop should be structured as for (int j = 1; j <= col; j++)
Inside the nested loop print ‘1’ to print ‘1′ in each column of a row.
Inside the main loop print a newline to move to the next line after a row. System.out.println();
Code in Java:
import java.util.Scanner;
public class Pattern1 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter row and col");
		int row = sc.nextInt();
		int col = sc.nextInt();
		for (int i = 1; i <= row; i++) {
			for (int j = 1; j <=col; j++) 
				System.out.print("1");
			System.out.println();
		}
	}

}
