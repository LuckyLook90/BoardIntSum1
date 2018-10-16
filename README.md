# BoardIntSum1
package pierwszeKroki.com.pl;

import java.util.Arrays;

public class BoardIntSum1 {

	
		public static void main(String[] args) {
	     // Metoda, która jako jedyny argument przyjmie zmienną typu int[] i zwróci sumę wszystkich elementów tablicy;
			int [] arr = {1,2,3,4};
			int sum = Arrays.stream(arr).sum();
			System.out.println(sum);
	}

}
