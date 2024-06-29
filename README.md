import java.util.Scanner;
public class main{
    public static void main(String [] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter date :");
        int day=sc.nextInt();
        if(day>7){
            day=day%7;
        }
        switch(day){
            case 1:
                System.out.println("Monday");
                break;
            case 2:
                System.out.println("Tuesday");
                break;
            case 3:
                System.out.println("wednesday");
                break;
            case 4:
                System.out.println("Thursday");
                break;
            case 5:
                System.out.println("Friday");
                break;
            case 6:
                System.out.println("saturday");
                break;
            default:
            System.out.println("Invalid");
            
            
        }
    }
}
