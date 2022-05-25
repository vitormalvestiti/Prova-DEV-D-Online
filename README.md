**Name: Vitor Campos Malvestiti** **Date: 05/25/2022 City/State: Araras-SP**



Question 1

-------------------------------------------------------------------
Given: 
1.	public class A { 
2.	public void print(){ System.out.println("x"); } 3.
 	} 
4.	public class B extends A { 
5.	public void print(){ System.out.println("y"); } 6.
 	} 
7.	public class Main{ 
8.	public static void main(String[] args) { 
9.	B test = new A(); 
10.	test.print(); 
11.	} 
12.	} 
------------------------------------------------------------------
R: **Output is alternative A = x**


Question 2 
 
 -----------------------------------------------------------------
	Given: 	 
1.	//****************************** 
2.	// file A.java 
3.	//****************************** 
4.	package a; 
5.	public class A { 
6.	private int x; 
7.	protected int y; 
8.	public int m1() {return x;} 
9.	} 
10.	//****************************** 11. // file B.java 
12.	//****************************** 
13.	package b; 
14.	import a.A; 
15.	public class B extends A { 
16.	private int z; 
17.	public void m2(A a){ 
18.	z = y; 
19.	z = a.x; 
20.	z = a.m1(); 
21.	}  	 	 
22.	}  	 	 	 
------------------------------------------------------------------

R:  **C. Only II and III are correct**


-----------------------------------------------------------------


Question 3

What are the major elements in an object model?

R: **C. Abstraction, encapsulation and hierarchy**


-----------------------------------------------------------------



Question 4

**Alternative C**
3->4 
1->6
2->9


-----------------------------------------------------------------



Question 5

 **Alternative A**
 Only II and III are correct
 

-----------------------------------------------------------------



Questions 6

**Alternative D**
Alternatives A, B and C are all correct.


-----------------------------------------------------------------



Question 7

Considering the following tables and data information, what would be the correct result of 
the SQL command below?

R: **B.   Abe**
        **Bob**
        **Chris**
        **Dan**
        

-----------------------------------------------------------------

Question 8

**Alternative D**

UNIX operating system
MINIX and UNIX operating system 
UNIX and Linux operating system


        
***Infinit Coins***

package InfinitCoins;


public class Main {

	private static void main(String[] args) {
		Main so = new Main();
		System.out.println(so.makeChange(10, 25));
	}

	public int makeChange(int n, int denom) {
		int next_denom = 0;
		switch (denom) {
		case 25:
			next_denom = 10;
			break;
		case 10:
			next_denom = 5;
			break;
		case 5:
			next_denom = 1;
			break;
		case 1:
			return 1;
		}
        default:
    		return 0;
    	}
		int ways = 0;
		for (int i = 0; i * denom <= n; i++) {
			ways += makeChange(n - i * denom, next_denom);
		}
		return ways;
	}
}

        

-----------------------------------------------------------------


**Qual a disciplina que você mais gostou de cursar na faculdade e por quê?**

Criação de sitios para internet e projeto de navegação e interação, pois estudamos e desenvolvemos conhecimentos nas areas
de front end, elaboração de layout, codificação de todo o front end, criação e manipulação de funções com java script.
É a parte que eu mais gosto (Front-End), então foi as que eu mais gostei de cursar e me identifiquei sobre tudo.