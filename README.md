# bat-programmer
import java.util.Scanner;
public class Bat
{
public static void main(String sh[])
{
Scanner sc=new Scanner(System.in);
int s, h;
s=sc.nextInt();
h=sc.nextInt();
sc.close();
batprog(s,h);
}
public static void batprog(int x,int y)
{
int sdsd=0;

for(int i=1;i<=x;i++)
{
sdsd=sdsd+y;
}
System.out.println(sdsd);
}
}
