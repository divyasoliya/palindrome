# palindrome
// Java program to reverse a number
// and find if it is a palindrome or not

class Demo
{  
     public static void main(String args[])
     {  
          int r,sum=0,temp;    
          int n=454;              //It is the number variable to be checked for palindrome  
          temp=n;    
          while(temp>0)
          {    
             r=n%10;               //getting remainder  
             sum=(sum*10) + r;     
             n=n/10;    
          }    
          if(n==sum)
          {
             System.out.println("palindrome number ");    
          }
          else 
          {
             System.out.println("not palindrome");  
          }
    }  
}  
