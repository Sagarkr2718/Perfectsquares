# Perfectsquares
Given a number A. Print all perfect squares less than or equal to A. Notes - Perfect squares are integers whose square root is an integer.
import java.lang.*;

import java.util.*;

public class Main {

    public static void main(String[] args) {
     
        Scanner sc = new Scanner(System.in);
		int N = sc.nextInt();
		int i =1;
		int j=1;
		while(j<=N){
			
			System.out.print(j+" ");
			++i;
			j=i*i;
        }
        
    }
}
