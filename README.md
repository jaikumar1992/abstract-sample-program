# abstract-sample-program
sample
// Abstraction sample program.
abstract class absttest
{
	int x =70;
	int y =86;
	
	public abstract void display();
	
	public void details()
	{
		System.out.println(" marks :"+x + " and  :"+y);
	}
}
class b extends absttest{
	public void display()
	{
		System.out.println(" ramesh marks");
	}
	public void details()
	{
		super.details();
	}
	public static void main(String []args)
	{
		b a= new b();
		a.display();
		a.details();
	}
}
