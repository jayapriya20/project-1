package Question4;

import java.util.*;

public class PriorityQueueDemo {

	private PriorityQueue<Product> pQueue;

	public PriorityQueueDemo()
	{
	      pQueue = new PriorityQueue<Product>();
	      init();
	} 
	
	void init()
	{
		 pQueue.add(new Product(101,"Dell Laptop",35000));
	     pQueue.add(new Product(52,"JBL Speaker",1500));
	     pQueue.add(new Product(63,"Realme 8 Pro Mobile",18000));	
	     pQueue.add(new Product(12,"OnePlus Ear Buds",5000));
	     pQueue.add(new Product(45,"MI Smart TV",50000));
	}
	
	public void sort1()
	{
		 System.out.println("Sorted Product by product price :");

		   for(Product p: pQueue)
		   {
				System.out.println(p);
		
		   }
	
	}
}