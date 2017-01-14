# Primenumbers
class Primenumbers
{
	public static void main (String[] args) 
	{
	    int i=0;
	    int num=0;
	    String  prime = "";
		for(i=1;i<=50;i++)
		{
		    int count=0;
		    for(num=i;num>=1;num--)
		    {
		        if(i%num==0)
		        {
		            count+=1;
		        }
		       
		    }
		    if (count==2)
	        {
	     	     prime= prime + i + " ";
	        }
	 	}
	    System.out.println(prime);
    }
}
