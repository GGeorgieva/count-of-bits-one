import java.util.Scanner;
public class _7_CountOfBitsOne {
	public static void main(String[] args) {
		Scanner input=new Scanner(System.in);
		int n=input.nextInt();
		int count=0;
		String binN=Integer.toBinaryString(n);		
		char[] bits=binN.toCharArray();		
		for (int i = 0; i < binN.length(); i++) {
			if (bits[i]=='1') {
				count++;
			}
		}
		System.out.println(count);
	}

}

