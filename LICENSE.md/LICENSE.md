package agoritma5;

import java.util.Scanner;

public class artikyil {

	public static void main(String[] args) {
		
		Scanner input = new Scanner(System.in);
		
		int sene = input.nextInt();
		
		
		if ((sene %4==0 && sene %100 !=0) || (sene %400==0))
		{
			System.out.println(sene +" senesi artık yıldır");
		}else
			System.out.println(sene+"senesi artık yıl değildir");

	}

}
