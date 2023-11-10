# DoWhileDC
DoWhileDC

package exemplos;

import java.util.Scanner;

;

public class ExemploDoWhileDC {

	public static void main(String[] args) {
		Scanner  sc = new Scanner(System.in);
		int x , r ;
		String resp;
		
		resp="sim";
		
		do {
			System.out.println("Digite um valor para ser multiplicado por 3 : ");
			x=sc.nextInt();
			r=x*3;
			System.out.println("A  resposta da multiplicação e :" + r);
			System.out.println("Deseja continuar ?");
			resp=sc.next();
		} while (resp.equals("sim"));

	}
	
	}
