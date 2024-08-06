import java.util.Scanner;
import java.io.*;
class Op
{
    int a,b,c;
    void cal_add(int a,int b)
    {
        int result=a+b;
        System.out.println("the add value is"+result);
    }
    
    public static void main(String args[])
    {
        Scanner s1=new Scanner(System.in);
        Op m1=new Op();
        m1.a=s1.nextInt();
        m1.b=s1.nextInt();
        m1.cal_add(m1.a,m1.b);
        
    }
}
