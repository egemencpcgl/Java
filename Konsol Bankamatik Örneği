//////////////////  BANKAMATÝK ÝSLEMLERÝ YAPTIRAN ////////////////
///////////////////////  CONSOLE UYGULAMASI   ////////////////////

import java.awt.*;
import java.util.Scanner;
import javax.swing.*;
import java.math.*;

public class konsolbankamatik {

	public static void main(String[] args) {
		int bakiye = 50;
		Scanner s = new Scanner(System.in);
		System.out.println("--------------");
		System.out.println("Console Bankamatige Hosgeldiniz");
		System.out.println("--------------");

		inner:while(true)
		{        
		System.out.println("--------------");
		System.out.println("Islem Turunu Secin");
		System.out.println("1 Para Yatirma");
		System.out.println("2 Para Cekme  ");
		System.out.println("3 Bakiye Sorma");
		System.out.println("4 Cikis");
		System.out.println("--------------");
		Scanner g = new Scanner(System.in);
		int islem = g.nextInt();
		switch(islem)  {		
		case 1:
		{
			Scanner p = new Scanner(System.in);
			System.out.println("--------------");
			System.out.println("Yatirilacak Tutari Giriniz");
			int q = p.nextInt();
			bakiye = bakiye+q;
			System.out.println("Paraniz hesabiniza yatirildi.");
			System.out.println("Bakiyeniz: "+bakiye);
			System.out.println("Baska islem yapmak icin C ' ye basin.");
			System.out.println("Cikis yapmak icin Q ' ya basin");
			System.out.print("Ýsleminiz: ");
			System.out.println("--------------");
			Scanner i = new Scanner(System.in);
			String sa = i.nextLine();
			switch(sa) {
			case "Q":
			{ 				
				break;
			}
			case "C":
			{
				continue inner;				
			}			
			}	
		}		
		case 2:			
		{
			Scanner p = new Scanner(System.in);
			System.out.println("--------------");
			System.out.print("Cekilecek Tutari Girin:");
			int q = p.nextInt();
			if (bakiye < q) {
				System.out.println("Bakiye yetersiz. Tekrar deneyiniz.");
				continue inner;
			}
			else {
			bakiye=bakiye-q;
			System.out.println("Para cekme islemi basariyla gerceklesti");
			System.out.println("Bakiyeniz: "+bakiye);
			System.out.println("Baska islem yapmak icin C ' ye basin.");
			System.out.println("Cikis yapmak icin Q ' ya basin");
			System.out.print("Ýsleminiz: ");
			System.out.println("--------------");
			Scanner i = new Scanner(System.in);
			String sa = i.nextLine();
			switch(sa) {
			case "Q":
			{ 				
				break;
			}
			case "C":
			{
				continue inner;				
			}			
			}	
		}}
		case 3:{
			System.out.println("--------------");
			System.out.println("Bakiyeniz: "+bakiye);
			System.out.println("Baska islem yapmak icin C ' ye basýn.");
			System.out.println("Cikis yapmak icin Q ' ya basýn");
			System.out.print("Ýsleminiz: ");
			System.out.println("--------------");
			Scanner i = new Scanner(System.in);
			String sa = i.nextLine();
			switch(sa) {
			case "Q":
			{ 				
				break;
			}
			case "C":
			{
				continue inner;				
			}			
			}
			}
		case 4:
		{
			System.out.println("Cikis Yapiliyor.");
			break inner;
		}
		}		
		}
	}
}
