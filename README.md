
//  program for method overriding
package javaprogram;

class Super
{
	
	void show()
	{
		System.out.println("Base class");
	}
}

public class methodOverrding extends Super
{

	void show()
	{
		super.show();
		System.out.println("Derive class");
	}
	public static void main(String[] args) {
		
		methodOverrding mo=new methodOverrding();
		mo.show();
		
	}
}
