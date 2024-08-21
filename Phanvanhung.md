import java.util.Scanner;

public class HelloWorld{

    public static void main(String args[]){
		Scanner sc = new Scanner(System.in);
	
        
       System.out.println("nhập a: ");
			int a = sc.nextInt();
		System.out.println("nhập b: ");
			int b = sc.nextInt();
		 System.out.println("cộng: " + a + " + " + b + " = " + (a+b));
        System.out.println("Trừ: " + a + " - " + b + " = " + (a - b));
        System.out.println("Nhân: " + a + " * " + b + " = " + (a * b));
	  if (b != 0) {
            System.out.println("Chia: " + a + " / " + b + " = " + ((int) a / b));
            System.out.println("Chia lấy dư: " + a + " % " + b + " = " + (a % b));
        } else {
            System.out.println("Không thể chia cho 0.");
        }
		
		
    }
}
