import java.util.*;

public class add {

    public static void main (String[] args){
    char stop;
do {
         try{
    
       
       
long a=0;
long digit,sum=0;

Scanner num=new Scanner (System.in);
System.out.println("Enter a number");
a=num.nextInt();
while(a>0)
{
digit=a%10;
sum+=digit;
a/=10;
}
System.out.println(sum);

 }
         catch(InputMismatchException e){//to runtime expection :-if user add sting 
         System.out.println("incorrect input only Interger value is valid !!!");
         }
         
         System.out.println("For exit the program press 'x' and \n To contnue press 'y'");
Scanner cont =new Scanner (System.in);
stop = cont.next().charAt(0);
}while(stop!='x' && stop=='y');
  
}
}
  
