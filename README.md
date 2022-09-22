# PALINDROME-
import java.util.*;

class Palindrome{  
	public static void main(String args[]){
		
		
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter a Number : ");
		int n=sc.nextInt();             //no variable to be checked for palindrome  
		int r,sum=0,temp;    
                  
       temp=n;    
     while(n>0){    
      r=n%10;                               //get remainder  
      sum=(sum*10)+r;    
      n=n/10;                               
  }
     if(temp==sum)                       //check wheteher condition is palindrome or not 
    	 System.out.println("Palindrome Number!!!");
     else
    	 System.out.println("Not Palindrome!!!!");    
  }  
}
