# Interface-in-Java

import java.util.*;

interface client 
{

    void get();
    
    void display();
};

class IFimplementsclient
{
    int a,b;
    
    void get()
    {
    
        Scanner sc = new Scanner(System.in);
        
        System.out.println("Enter your id:");
        
        a = sc.nextInt();
        
        System.out.println("Enter your DOB:");
        
        b = sc.nextInt();
    }
    
    void display()
    {
    
        System.out.println("Your ID is: "+a);
        
        System.out.println("Enter Date of Birth is: "+b);
    }
    public static void main(String args[])
    {
        IFimplementsclient i = new IFimplementsclient();
        
        i.get();
        
        i.display();
    }
}
