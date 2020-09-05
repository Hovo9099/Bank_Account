import java.util.Scanner;
import java.lang.Math;
//160
class Main {
  public static void main(String[] args) {
    Scanner sc =new Scanner(System.in);
    int n;
    
    for(int i=100;i<1000;i++){
      n=(int)Math.sqrt(i*16);
        
        if(Math.pow(n,2)==i*16)
           System.out.println(i);  
           
           
    }  
  }
}
