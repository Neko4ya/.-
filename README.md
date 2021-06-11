# .-import java.util.Scanner;

public class Team {	
	
	public static void main(String[] args) {
		
		create();
		
		
	}

	
		public static void create() {

			
			String name1 = "Marc-Andre ter Stegen";
			short age1 = 29;
			
			String name2 = "Emre Can";
			short age2 = 27;
			
			String name3 = "Matthias Ginter";
			short age3 = 27;
			
			String name4 = "Antonio Rüdiger";
			short age4 = 28;
			
			String name5 = "Joshua Kimmich";
			short age5 = 26;
			
			String name6 = "Robin Gosens";
			short age6 = 27;
			
			String name7 = "Leon Goretzka";
			short age7 = 26;
			
			String name8 = "Leroy Sane";
			short age8 = 25;
			
			String name9 = "Kai Havertz";
			short age9 = 22;
			
			String name10 = "Serge Gnabry";
			short age10 = 26;
			
			String name11 = "Ilkay Gündogan";
			short age11 = 31;
			
			
			
			
			
			String name01 = "Jose Moreira";		
			short age01 = 29;	//39
			
			String name02 = "Paaulo Ferreira";
			short age02 = 22;	//42
			
			String name03 = "Rui Jorge";
			short age03 = 28;	//48
			
			String name04 = "Jorge Andrade";
			short age04 = 23;	//43
			
			String name05 = "Luis Figo";
			short age05 = 29;	//49
			
			String name06 = "Rui Costa";
			short age06 = 29;	//49
			
			String name07 = "Simao Sabrosa";
			short age07 = 22;	//42
			
			String name08 = "Cristano Ronaldo";
			short age08 = 26;	//36
			
			String name09 = "Pauleta";
			short age09 = 28;	//48
			
			String name010 = "Nuno Gomes";
			short age010 = 25;	//45
			
			String name011 = "Helder Postiga";
			short age011 = 29;	//39
			
			
			
			
			String name001 = "Marc-Andre ter Stegen";
			short age001 = 30;	//40
			
			String name002 = "Emre Can";
			short age002 = 29;	//39
			
			String name003 = "Matthias Ginter";
			short age003 = 27;	//37
			
			String name004 = "Antonio Rüdiger";
			short age004 = 25;	//35
			
			String name005 = "Joshua Kimmich";
			short age005 = 23;	//33
			
			String name006 = "Robin Gosens";
			short age006 = 19;	//29
			
			String name007 = "Leon Goretzka";
			short age007 = 24;	//34
			
			String name008 = "Leroy Sane";
			short age008 = 24;	//34
			
			String name009 = "Kai Havertz";
			short age009 = 23;	//33
			
			String name0010 = "Serge Gnabry";
			short age0010 = 30;	//40
			
			String name0011 = "Ilkay Gündogan";
			short age0011 = 27;	//37
			
			
		
			
			
			Scanner scanner = new Scanner(System.in);
			String input = "";
			
			
			System.out.println("");
			
			System.out.println("Player 1:	");
			String player1 = scanner.nextLine();
			
			System.out.println("Player 2:	");
			String player2 = scanner.nextLine();
			
			System.out.println("Player 3:	");
			String player3 = scanner.nextLine();
			
			System.out.println("Player 4:	");
			String player4 = scanner.nextLine();
			
			System.out.println("Player 5:	");
			String player5 = scanner.nextLine();
			
			System.out.println("Player 6:	");
			String player6 = scanner.nextLine();
			
			System.out.println("Player 7:	");
			String player7 = scanner.nextLine();
			
			System.out.println("Player 8:	");
			String player8 = scanner.nextLine();
			
			System.out.println("Player 9:	");
			String player9 = scanner.nextLine();
			
			System.out.println("Player 10:	");
			String player10 = scanner.nextLine();
			
			System.out.println("Player 11:	");
			String player11 = scanner.nextLine();
			

			
			
			
			
			input = Character.toString(scanner.nextLine().toLowerCase().charAt(0));
			
			switch (input) {
					
			case "q":
				System.out.println(name1 + " Age " + " :" + age1);
				break;
			case "w":
				System.out.println( name2 + " Age " + " :" + age2);
				break;
			case "e":
				System.out.println( name3 + " Age " + " :" + age3);
				break;
			case "r":
				System.out.println( name4 + " Age " + " :" + age4);
				break;
			case "t":
				System.out.println( name5 + " Age " + " :" + age5);
				break;
			case "z":
				System.out.println(name6 + " Age " + " :" + age6);
				break;
			case "u":
				System.out.println(name7 + " Age " + " :" + age7);
				break;
			case "i":
				System.out.println(name8 + " Age " + " :" + age8);
				break;
			case "o":
				System.out.println(name9 + " Age " + " :" + age9);
				break;
			case "p":
				System.out.println(name10 + " Age " + " :" + age10);
				break;
			case "ü":
				System.out.println(name11 + " Age " + " :" + age11);
				break;

				
				
			case "a":
				System.out.println(name01 + " Age " + " :" + age01);
				break;
			case "s":
				System.out.println(name02 + " Age " + " :" + age02);
				break;
			case "d":
				System.out.println(name03 + " Age " + " :" + age03);
				break;
			case "f":
				System.out.println(name04 + " Age " + " :" + age04);
				break;
			case "g":
				System.out.println(name05 + " Age " + " :" + age05);
				break;
			case "h":
				System.out.println(name06 + " Age " + " :" + age06);
				break;
			case "j":
				System.out.println(name07 + " Age " + " :" + age07);
				break;
			case "k":
				System.out.println(name08 + " Age " + " :" + age08);
				break;
			case "l":
				System.out.println(name09 + " Age " + " :" + age09);
				break;
			case "ö":
				System.out.println(name010 + " Age " + " :" + age010);
				break;
			case "ä":
				System.out.println(name011 + " Age " + " :" + age011);
				break;

				
			case "1":
				System.out.println(name001 + " Age " + " :" + age001);
				break;
			case "2":
				System.out.println(name002 + " Age " + " :" + age002);
				break;
			case "3":
				System.out.println(name003 + " Age " + " :" + age003);
				break;
			case "4":
				System.out.println(name004 + " Age " + " :" + age004);
				break;
			case "5":
				System.out.println(name005 + " Age " + " :" + age005);
				break;
			case "6":
				System.out.println(name006 + " Age " + " :" + age006);
				break;
			case "7":
				System.out.println(name007 + " Age " + " :" + age007);
				break;
			case "8":
				System.out.println(name008 + " Age " + " :" + age008);
				break;
			case "9":
				System.out.println(name009 + " Age " + " :" + age009);
				break;
			case "x":
				System.out.println(name0010 + " Age " + " :" + age0010);
				break;
			case "y":
				System.out.println( name0011 + " Age " + " :" + age0011);
			break;
			
			
			}
			
			
			
			
			System.out.println(player1);
			System.out.println(player2);
			System.out.println(player3);
			System.out.println(player4);
			System.out.println(player5);
			System.out.println(player6);
			System.out.println(player7);
			System.out.println(player8);
			System.out.println(player9);
			System.out.println(player10);
			System.out.println(player11);
			
			
			
//			System.out.println(player01);
//			System.out.println(player02);
//			System.out.println(player03);
//			System.out.println(player04);
//			System.out.println(player05);
//			System.out.println(player06);
//			System.out.println(player07);
//			System.out.println(player08);
//			System.out.println(player09);
//			System.out.println(player010);
			//System.out.println(player011);
						
			
			

			
		}
		

	}


