import java.util.Scanner;

class Main{                                     //basically gthis is for print odd or even number 
    public static void main(String[]arggs){
        int n;
        System.out.print("Enter Value");
        Scanner r=new Scanner(System.in);
        n=r.nextInt();
        if (n%2==0)
        {
            System.out.print("Even");
        }
        else
        {
            System.out.print("ODD");
        }
    }
}
