
public class first {

	public static void main(String[] args) {
		
		 for(int i =0; i<10;i++)
	        {
	            if(i==2 )
	            {
	                for(int j=0;j<=i;j++)
	                {
	                    System.out.print("*");
	                }
	                System.out.println();
	            }
		        
	            else if(i==5)
		            {
		                for(int k=0;k<=i;k++)
		                {
		                    System.out.print("*");
		                }
		                System.out.println();
		            }
	            else if( i==9)
	            {
	                for(int k=0;k<i+1;k++)
	                {
	                    System.out.print("*");
	                }
	                System.out.println();
	            }
	            else if(i<2)
	            {
	                System.out.println('*');
	            }
	            else if(i>2 && i<5)
	            {
	                System.out.println("**");
	            }
	            else
	            {
	                System.out.println("***");
	            }
	        }
	    }
	

	}

