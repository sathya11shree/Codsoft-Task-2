# Codsoft-Task-1
import java.util.Scanner;
public class Main
{
    public static char Grade(int avg)
    {
        
        if(avg>= 90)
        {
            return 'A';
        }
        else if (avg >= 80)
        {
            return 'B';
        }
        else if (avg >= 70)
        {
            return 'C';
        }
        else if (avg >= 60)
        {
            return 'D';
        }
        else  
        {
            return 'F';
        }
    }
	public static void main(String[] args) 
	{
	    Scanner sc = new Scanner (System.in);
	    
	    System.out.println("Enter Name of the Student: ");
	    String name = sc.nextLine();//to get the name of the student
	    
	    System.out.println("\nEnter RollNo of the Student: ");
	    int Rollno = sc.nextInt();//to get the rollno of the student
	    
		System.out.println("\nEnter Number of Subjects: ");
		int no = sc.nextInt();//to get the no of subjects
		
		int Tot = 0;
		for(int i=0;i<no;i++)
		{
		    System.out.println("\nEnter Each Subject Mark "+(i+1)+": ");
		    int marks=sc.nextInt();//to get the mark of each subject
		    Tot +=marks;
		}
		int Avg = (Tot/no);
		System.out.println("\nTotal: "+Tot +
		                  "\nAverage: "+Avg +
		                  "\nGrade: "+Grade(Avg));
		
	}
	
	
}
