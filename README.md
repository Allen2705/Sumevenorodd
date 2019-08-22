import java.util.Scanner;
class Sumevenorodd{
public static void main(String args[]){
int a,b,r,s,sum=0,sum1=0,p;
Scanner scan = new Scanner(System.in);
a = scan.nextInt();
b = scan.nextInt()
while(a>0){
r=a%10;
sum=sum+r;
a=a/10;
}
while(b>0){
s=c%10;
sum1=sum1+s;
b=b/10;
}
p=sum+sum1;

if (p%2==0)
{
System.out.print("Even");
}
else
{
System.out.print("Odd");
}
}
}
