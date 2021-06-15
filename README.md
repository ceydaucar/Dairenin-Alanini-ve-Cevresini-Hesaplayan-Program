# PatikaDevJava101pratik3
import java.util.*;
public class pratik3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Yarı çap değeri girin: ");
		int r = sc.nextInt();
		
		System.out.println("Merkez açı ölçüsü değeri girin: ");
		int a = sc.nextInt();
		
		final double PI = 3.14;
		double alan = (PI * (r * r) * a) /360;
		
		System.out.println("Yarıçapı r, merkez açısının ölçüsü a olan daire diliminin alanı: " + alan);
		
	}

}
