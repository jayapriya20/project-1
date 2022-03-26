package Question2;

public class BookMain{
	public static void main(String gg[])
	{
	BookCollection bc=new BookCollection("Akshata Pukle");
	Book b=new Book(109, "power of mind", "bar");
	System.out.println("Book already exist :"+bc.hasBook(b));
	bc.toString();
	System.out.println("\n");
	
	bc.sort1();
	System.out.println("\n");
	bc.sort2();
	}
}