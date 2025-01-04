# practice.java-program
import java.util.Scanner;
public class Main{
    public static void main(String[] args){
        int f,s,t,count;
        Scanner obj=new Scanner(System.in);
        System.out.print("enter");
        count=obj.nextInt();
        f=0;
        s=1;
        for(int i=1;i<=count;i++){
            System.out.print(f+"");
            
            t=f+s;
            f=s;
            s=t;
            
            System.out.print(t+"");
        }
        obj.close();
       
    }
}
