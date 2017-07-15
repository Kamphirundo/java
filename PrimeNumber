package interest;//输入一个正整数，罗列出所有质数，计数并计时

import java.util.Scanner;

public class PrimeNumber {
	
	 	public static void main(String[] args) {
	 		System.out.println("请输入一个正整数：");
	 		Scanner scan =new Scanner(System.in);
	 		int x =scan.nextInt();
	 		scan.close();
	 		int num =0;
			long t1=System.currentTimeMillis();
			for(int a=2;a<=x;a++){
				double b=Math.sqrt(a);
				int c=2;
				for(;c<=b;c++){
					if(a%c==0){
						break;
					}
				}
				if(c>b){
					System.out.print(a+"\t");
					if(++num%10==0){
						System.out.println();
					}
				}
				
			}
			long t2=System.currentTimeMillis();
			System.out.println();
			System.out.println("质数总数为"+num);
			System.out.println("总共耗时"+(t2-t1)+"毫秒");
			
		}

}
