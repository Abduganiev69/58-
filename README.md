# 58-
57Перевязь
public class Main
{
	public static void main(String[] args) {
	     java.util.Scanner myscanner= new java.util.Scanner(System.in);
	 	int a = myscanner.nextInt();
	 	
	 	if (a % 10 != 0) {
	          System.out.println(a/10+1);
	 	}else{
	 	     System.out.println(a/10);
	 	}
	}
}
