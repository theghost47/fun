import java.util.*;

public class Main {
	public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);
		System.out.println("\nPlayer1: ");
		String P1 = scan.nextLine();
		System.out.println("\nPlayer2: ");
		String P2 = scan.nextLine();
		char a = 'a';
		char b = 'b';
		char c = 'c';
		char d = 'd';
		char e = 'e';
		char f = 'f';
		char g = 'g';
		char h = 'h';
		char i = 'i';
		Boolean end = false; 
		int counting_moves = 0;
		do{
			System.out.println(" "+ a +"  | "+b+" | "+c+" ");
			System.out.println("-------------");
			System.out.println(" "+ d +"  | "+e+" | "+f+" ");
			System.out.println("-------------");
			System.out.println(" "+ g +"  | "+h+" | "+i+" ");
			char n ;
			String in;
			do{
				if(counting_moves % 2 == 0) {
					n = 'X';
					System.out.println("\n"+ P1 +" enter position :");
				}else { 
					n = 'O';
					System.out.println("\n"+ P2 +" enter position :");
				}
				in = scan.nextLine();
				System.out.println("");
			}while(in.isBlank()) ;
			switch (in){ 
			case"a":
					a = n;break;
			case"b":
					b = n;break;
			case"c":
					c = n;break;
			case"d":
					d = n;break;
			case"e":
					e = n;break;
			case"f":
					f = n;break;
			case"g":
					g = n;break;
			case"h":
					h = n;break;
			case"i":
					i = n;break;
			}
			if(a == n && b == n &&c == n) {
				System.out.println(n + " wins");
				end = true;
			}else if (a == n && e == n && i == n) {
				System.out.println(n + " wins");
				end = true;
			}else if (a == n && d == n && g == n) {
				System.out.println(n + " wins");
				end = true;
			}else if(b == n && e == n && h == n) {
				System.out.println(n + " wins");
				end = true;
			}else if (c == n && f == n && i == n) {
				System.out.println(n + " wins");
				end = true;
			}else if (d == n && e == n && f == n) {
				System.out.println(n + " wins");
				end = true;
			}else if (g == n && h == n && i == n) {
				System.out.println(n + " wins");
				end = true;
			}
			counting_moves ++;
		}while(!end);
		scan.close();
	}
}
