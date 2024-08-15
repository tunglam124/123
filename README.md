import java.util.Scanner;
public class doitien {
	static double exchange = 23500.0;
	public static void main (String [] args) {
		Scanner x = new Scanner(System.in);
		System.out.println("Vui long nhap so USD can doi: ");
		double usd = x.nextDouble();
		double vnd = usd*exchange;
		System.out.println("So VND sau khi doi la  = " + vnd);
	}
}
