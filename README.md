// table for user choice
import java.util.*;
public class Table {

	public static void main(String[] args) {
		
		
		Scanner sc=new Scanner(System.in);
		System.out.println("please enter the table limit");
		int limit=sc.nextInt();
		
		for(int i=1;i<=10;i++)
		{
			for(int j=1;j<=limit;j++)
			{
				System.out.print(i*j+"  ");
			}
			System.out.print("\n");
		}
		
	}

}
