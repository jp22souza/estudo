import java.util.Scanner;



public class Java_for {

    public static void main(String[] args) {
        
      Scanner Sc = new Scanner (System.in);
		
	int x = Sc.nextInt ();
         for (int i=1;i<=x; i++){
            if (i% 2!=0){
            
	 System.out.println(i);
            }
         }
		
		Sc.close();
	}

