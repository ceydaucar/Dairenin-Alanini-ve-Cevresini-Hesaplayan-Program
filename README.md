# PatikaDevJava101pratik3
import java.util.*;
public class pratik3 {

	public static void main(String[] args) {
		// Yeni bir tarayıcı(scanner) oluştur.
		Scanner sc = new Scanner(System.in);
		
		// Kullanıcıdan yarıçap ve merkez açı ölçüsü değerlerini al. 
		System.out.println("Yarıçap değeri girin: ");
		int r = sc.nextInt();
		
		System.out.println("Merkez açı ölçüsü değeri girin: ");
		int a = sc.nextInt();
		
		// Pi sayısını ve formülü yazdır.
		final double PI = 3.14;
		double alan = (PI * (r * r) * a) /360;
		
		//Sonucu yazdır.
		System.out.println("Yarıçapı r, merkez açısının ölçüsü a olan daire diliminin alanı: " + alan);
		
	}

}
