# Dairenin Alanını ve Çevresini Hesaplayan Program
Patika.dev > Java101 > Temel Kavramlar ve Değişkenler > Pratik5 - Dairenin Alanını ve Çevresini Hesaplayan Program

## Yarıçapı r, merkez açısının ölçüsü 𝛼 olan daire diliminin alanı bulan programı yazınız.

- 𝜋 sayısını = 3.14 alınız.
- Formül : (𝜋 * (r*r) * 𝛼) / 360

		import java.util.*;
		public class pratik3 {

			public static void main(String[] args) {
				// Yeni bir tarayıcı(scanner) oluştur.
				Scanner sc = new Scanner(System.in);
		
				// Kullanıcıdan yarıçap ve merkez açı ölçüsü değerlerini al. 
				System.out.println("Yarıçap değeri girin: ");
				int r = sc.nextInt();
		
				System.out.println("Merkez açı ölçüsü değeri girin: ");
				int 𝛼 = sc.nextInt();
		
				// Pi sayısını ve formülü yazdır.
				final double PI = 3.14;
				double alan = (PI * (r * r) * 𝛼) /360;
		
				//Sonucu yazdır.
				System.out.println("Yarıçapı r, merkez açısının ölçüsü 𝛼 olan daire diliminin alanı: " + alan);
		
			}
		}
