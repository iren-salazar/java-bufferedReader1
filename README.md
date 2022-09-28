# java-bufferedReader1
tanan kay buffered readline -(string) lang walay integer sah


package oopexercise;//BufferedReeaderByMaritesCoder

import java.io.*;

public class BufferReader {
	public static void main (String args []) throws Exception {
		
		BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
		
		System.out.println("Enter first number: ");
		double num1 = Double.parseDouble(br.readLine());
		System.out.println("Enter second number: ");
		double num2 = Double.parseDouble(br.readLine());
		System.out.println("Enter third number: ");
		double num3 = Double.parseDouble(br.readLine());
		System.out.println("Enter fourth number: ");
		double num4 = Double.parseDouble(br.readLine());
		
		double sum = num1+num2+num3+num4;
		//int min, max;
		System.out.println("Sum:"+sum);
		System.out.println("Difference:"+(num1-num2-num3-num4));
		//System.out.println("Max:"+max);
		//System.out.println("Min:"+min);
	}
}

