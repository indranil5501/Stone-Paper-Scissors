import java.util.Random;
import java.util.*;
public class s_p_s{
public static void main(String[] args){
Random rand = new Random();
Scanner sc=new Scanner(System.in);
System.out.println("----------------------------------------------welcome to our game-----------------------------------------------------\n\n");
System.out.println("--------------------------------you have to complte the game after playing 5 round with computer--------------------------\n\n");
System.out.println("-------------let's start the game-------------\n\n");

int i=0;
int user=0;
int computer=0;

while(i<5)
{
 System.out.println("-------------enter 1 for choose stone-------------\n:");
System.out.println("--------------enter 2 for choose paper-------------\n:");
System.out.println("--------------enter 0 for choose scissor-------------\n:");
System.out.println("-------------enter 3   for    exit the game-------------\n:");
int n=sc.nextInt();
int Rand=rand.nextInt(3);


  
  switch(n)
{
 case 1:
    System.out.println("you choose stone");
    if(Rand == 2)
    {
      System.out.println("computer takes paper:");
      System.out.println("computer is win");
      computer++;
    }
    if(Rand == 0)
    {
       System.out.println("computer takes scissor");
       System.out.println("you win");
       user++;
    }
    if(Rand == 1)
    {
       System.out.println("computer takes also stone");
       System.out.println("draw");
       
    }
    break;
case 2:
    System.out.println("you choose paper");
    if(Rand == 0)
    {
       System.out.println("computer takes scissor");
      System.out.println("computer is win");
      computer++;
    }
    if(Rand == 1)
    {
       System.out.println("computer takes stone");
       System.out.println("you win");
       user++;
    }
    if(Rand == 2)
    {
       System.out.println("computer also takes paper");
       
       System.out.println("draw");
       
    }
    break;
case 0:
   System.out.println("you choose scissor");
   if(Rand == 1)
    {
      System.out.println("computer takes stone");
      System.out.println("computer is win");
      computer++;
    }
    if(Rand == 2)
    {
       System.out.println("computer takes paper");
       System.out.println("you win");
       user++;
    }
   if(Rand == 0)
    {
       System.out.println("computer also takes scissor");
       System.out.println("draw");
       
    }
    break;
default:
   
   break;
}
i++;

  
}
System.out.println("the result of this entire game is");
if(computer>user)
{
  System.out.println("\n\n********computer is win in this game******");
}
else
{
   System.out.println("\n\n*********congratilations! you is win in this game*******");
}
System.out.println("\n-------------thanks for playing the game-------------:");
}
}
