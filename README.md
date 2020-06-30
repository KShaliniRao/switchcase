# switchcase

package Switchcase;

import java.util.Scanner;

public class Switchcase {
    
    public static void main(String[] args) {
        int choice;
        System.out.println("Pick one : 1.Hi\t2.Hey\t3.hello\t");
        Scanner s = new Scanner(System.in);
        choice =s.nextInt();
        switch(choice)
        {
            case 1 : System.out.println("You said Hi");
                     break;
            case 2 : System.out.println("You said Hey"); 
                     break;
            case 3 : System.out.println("You said Hello");
                     break;
            default : System.out.println("Invalid choice");         
        }
    }    
}

OUTPUT=>

Pick one : 1.Hi	2.Hey	3.hello	
1
You said Hi
