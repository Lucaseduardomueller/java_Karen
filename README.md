# java_Karen
package atividade1;
 
public class ex1 {
 
    public static void main(String[] args) {
        System.out.println("Hello World!");
 
    }
 
}

—-----------------------------------------------------------

package atividade1;

public class ex2 {

	public static void main(String[] args) {
		System.out.println("É preciso fazer todos os algoritmos para aprender");

	}

}
—------------------------------------------------------------------------------

package atividade1;

public class ex3 {

	public static void main(String[] args) {
		System.out.println("Lucas Eduardo Mueller(O cria :P)");

	}

}
—------------------------------------------------------------------------------------

package atividade1;

public class ex4 {

	public static void main(String[] args) {
		System.out.println(28 * 43);
	}

}
—---------------------------------------------------------------------------
package atividade1;

public class ex5 {

	public static void main(String[] args) {
		double media;
		media = (8+9+7)/3;
		System.out.println(media);
	}

}
—--------------------------------------------------------------------
package atividade1;

public class ex6 {

	public static void main(String[] args) {
		int x;
		x = 365;
		System.out.println(x);
	}

}
—------------------------------------------------------------------

package atividade1;

public class ex7 {

	public static void main(String[] args) {
		String y = "Estou aprendendo java";
		System.out.println(y);

	}

}
—------------------------------------------------------------------
package atividade1;

public class ex8 {

	public static void main(String[] args) {
		int idade = 17;
		System.out.println("Minha idade é " + idade);

	}

}
—-----------------------------------------------------------------------

package atividade1;

import java.util.Scanner;

public class ex9 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int num;
		System.out.println("Numero");
		num = sc.nextInt();
		System.out.println(num);

	}

}
—--------------------------------------------------------------------
package atividade1;

import java.util.Scanner;

public class ex10 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int numero;
		int sus;
		int ant;
		
		System.out.println("Numero:");
		numero = sc.nextInt();
		
		sus = numero + 1;
		ant = numero - 1;
		
		System.out.println(ant);
		System.out.println(sus);

	}

}
—----------------------------------------------------------------------------------------
package atividade1;

import java.util.Scanner;

public class ex11 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("nome:");
		String nome = sc.next();
		System.out.println("endereço:");
		String endereco = sc.next();
		System.out.println("telefone:");
		int tel = sc.nextInt();
		System.out.println("Nome: " + nome + "Endereço: " + endereco + "Telefone: " + tel);

	}

}
—---------------------------------------------------------------------
package atividade1;

import java.util.Scanner;

public class ex12 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Numero:");
		int num1 = sc.nextInt();
		System.out.println("Outro Numero:");
		int num2 = sc.nextInt();
		
		int soma = num1 + num2;
		
		System.out.println(soma);

	}

}
—------------------------------------------------------------------
package atividade1;

import java.util.Scanner;

public class ex13 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Numero:");
		int num1 = sc.nextInt();
		System.out.println("Outro Numero:");
		int num2 = sc.nextInt();
		
		int produto = num1 * num2;
		
		System.out.println(produto);

	}

}
—---------------------------------------------------------------
package atividade1;

import java.util.Scanner;

public class ex14 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("número:");
		double num = sc.nextDouble();
		double terca = num / 3;
		System.out.println(terca);

	}

}
—------------------------------------------------------------
package atividade1;

import java.util.Scanner;

public class ex15 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("numero");
		int num1 = sc.nextInt();
		System.out.println("numero");
		int num2 = sc.nextInt();
		
		double media = (num1 + num2)/2;
		
		System.out.println("Média "+media);

	}

}
—-----------------------------------------------------------

package atividade1;

import java.util.Scanner;

public class ex16 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("base:");
		double base = sc.nextDouble();
		System.out.println("Altura");
		double altura = sc.nextDouble();

		double peri = base + base + altura + altura;
		double area = base * altura;
		
		System.out.println(area);
		System.out.println(peri);

	}

}
—--------------------------------------------------------------
package atividade1;

import java.util.Scanner;

public class ex17 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Digite o raio:");
		double raio = sc.nextDouble();

		double peri = 2 * 3.14 * raio;
		double area = 3.14 * (raio * raio);
		System.out.println(peri);
		System.out.println(area);

	}

}
—------------------------------------------------------------
package atividade1;

import java.util.Scanner;

public class ex18 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("base:");
		double base = sc.nextDouble();
		System.out.println("Altura");
		double altura = sc.nextDouble();

		double area = base * altura / 2;

		System.out.println(area);

	}

}
—--------------------------------------------------------
package atividade1;

public class ex19 {

	public static void main(String[] args) {
		double media;
		media = (8 + 9 + 7) / 3;
		
		double media2;
		media2 = (4 + 5 + 6) / 3;
		
		double medias = media + media2;
		double Meedia = medias / 2;
		
		System.out.println(medias);
		System.out.println(Meedia);

	}

}
—-------------------------------------------------------
package atividade1;

import java.util.Scanner;

public class ex20 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("anos:");
		int ano = sc.nextInt();
		System.out.println("meses");
		int mes = sc.nextInt();
		System.out.println("dias");
		int dia = sc.nextInt();
		
		int idadedias = (ano*365)+(mes*30)+dia;
	
		System.out.println("Sua idade em dias eh "+idadedias);
		
	}

}
------------------------------------------------------
atividade 2
------------------------------------------------------
import java.util.Scanner;

public class a {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int a,b,result;
		
		System.out.println("número:");
		a = sc.nextInt();
		System.out.println("outro número");
		b = sc.nextInt();
		
		result= a-b;
		System.out.println(result);
		

	}

}
-----------------------------------------------
import java.util.Scanner;

public class b {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int a,b,c,result;
		
		System.out.println("Número:");
		a = sc.nextInt();
		System.out.println("Outro numero:");
		b = sc.nextInt();
		System.out.println("Mais um numero:");
		c = sc.nextInt();
		
		result = a*b*c;
		
		System.out.println(result);

	}

}
--------------------------------------------
import java.util.Scanner;

public class c {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double a,b,result;
		
		System.out.println("Número:");
		a = sc.nextDouble();
		System.out.println("Número:");
		b = sc.nextDouble();
		
		result = a/b;
		
		System.out.println(result);
	}

}
--------------------------------------
import java.util.Scanner;

public class d {

	public static void main(String[] args) {
		double prod,desc;
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Digite o preço do produto:");
		prod = sc.nextDouble();
		
		desc = prod*0.90;
		
		System.out.println("O desconto de 10% sobre seu produto é de: "+desc);

	}

}
------------------------------------------
import java.util.Scanner;

public class e {

	public static void main(String[] args) {
		double sal,venda,com,salfinal;
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Digite seu salário:");
		sal = sc.nextDouble();
		System.out.println("Digite seu salário:");
		venda = sc.nextDouble();
		
		com = venda*0.04;
		salfinal = sal + com;
		
		System.out.println(salfinal);

	}

}
-------------------------------------------------
import java.util.Scanner;

public class f {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double sal,minimo,qtdsalario;
		
		System.out.println("Salário mínimo:");
		minimo = sc.nextDouble();
		System.out.println("Salário:");
		sal = sc.nextDouble();
		
		qtdsalario = sal/minimo;
		
		System.out.println(qtdsalario);
		

	}

}
-----------------------------------------------
import java.util.Scanner;

public class g {

	public static void main(String[] args) {
		int num, res;
		Scanner sc = new Scanner(System.in);

		System.out.println("número:");
		num = sc.nextInt();

		for (int i = 1; i <= 10; i++) {
			res = num * i;
			System.out.println(num + " x " + i + " = " + res);
		}
		sc.close();
	}

}
-----------------------------------
import java.util.Scanner;

public class h {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double sal,conta1,conta2,finalconta1,finalconta2,salfinal;
		
		System.out.println("Digite seu salário:");
		sal = sc.nextDouble();
		
		System.out.println("Digite o valor de sua conta:");
		conta1 = sc.nextDouble();
		
		System.out.println("Digite o valor de sua outra conta:");
		conta2 = sc.nextDouble();
		
		finalconta1 = conta1*1.02;
		finalconta2 = conta2*1.02;
		salfinal = sal - finalconta1 - finalconta2;

		System.out.println(salfinal);
	}

}
------------------------------------
import java.util.Scanner;

public class i {

	public static void main(String[] args) {
		double hrs,sal,extras,salhoras,valextras,salbruto,salextras,salfinal;
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Digite o número de horas trabalhadas:");
		hrs = sc.nextDouble();
		
		System.out.println("Digite seu salário mínimo:");
		sal = sc.nextDouble();
		
		System.out.println("Digite as suas horas extras:");
		extras = sc.nextDouble();
		
		salhoras = sal/8;
		valextras = sal/4;
		salbruto = hrs * salhoras;
		salextras = valextras * extras;
		salfinal = salbruto*salextras;
		
		System.out.println("O salário final é de: "+salfinal);
		
		

	}

}
------------------------------------------
import java.util.Scanner;

public class j {

	public static void main(String[] args) {
		Double qtddin,dindolar,dineuro,dinlibra;
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Digite a quantidade de dinheiro que vc tem: ");
		qtddin = sc.nextDouble();
		
		dindolar = qtddin * 4.97;
		dineuro = qtddin * 5.23;
		dinlibra = qtddin * 6.24;

		System.out.println("para dolar: "+dindolar);
		System.out.println("para euro: "+dineuro);
		System.out.println("para libra: "+dinlibra);



	}

}
-------------------------------------
import java.util.Scanner;

public class k {

	public static void main(String[] args) {
		double hrs, min, hrsmin, totalmin, minseg;
		Scanner sc = new Scanner(System.in);

		System.out.println("Horas:");
		hrs = sc.nextDouble();
		System.out.println("Minutos:");
		min = sc.nextDouble();

		hrsmin = hrs * 60;
		totalmin = hrsmin + min;
		minseg = (totalmin + min) * 60;

		System.out.println(hrs + "hrs = " + hrsmin);
		System.out.println("o total de minutos é: " + totalmin);
		System.out.println("O total de seg é: " + minseg);


	}

}
--------------------------------------
import java.util.Scanner;

public class l {

	public static void main(String[] args) {
		double custo,ingresso,qtd;
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Custo:");
		custo = sc.nextDouble();
		
		System.out.println("Ingresso:");
		ingresso = sc.nextDouble();
		
		qtd = custo/ingresso;
		
		System.out.println("A quantidade de ingressos deverá ser de: "+qtd);
		
	}

}
----------------------------------
import java.util.Scanner;

public class m {

	public static void main(String[] args) {
		double sal,qtdW,Kw,Wtotal,desconto;
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Salário:");
		sal = sc.nextDouble();
		System.out.println("QuiloWhatts consumido na residência:");
		qtdW = sc.nextDouble();
		
		Kw = sal/5;
		Wtotal = Kw * qtdW;
		desconto = Wtotal*0.85;
		
		System.out.println("vai ser pago o total de: "+desconto);
	}

}
------------------------------------------
import java.util.Scanner;

public class n {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double saco,qtdracao,gsaco,dia5,kg;
		
		System.out.println("Peso do saco:");
		saco = sc.nextDouble();
		System.out.println("Qtd ração:");
		qtdracao = sc.nextDouble();
		
		gsaco = saco*1000;
		
		dia5 = gsaco - ((qtdracao*2)*5);
		kg = dia5/1000;
		
		System.out.println(kg);
	}

}
---------------------------------------------
atividade if
---------------------------------------------
package funcoes;

import java.util.Scanner;

public class q1 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double a,b,c,x,delta,x1,x2;
		System.out.println("informe o valor de a:");
		a = sc.nextDouble();
		System.out.println("informe o valor de b:");
		b = sc.nextDouble();
		System.out.println("informe o valor de c:");
		c = sc.nextDouble();
		delta = Math.pow(b, 2) - 4*a*c;
		x1 = (-b+Math.sqrt(delta))/2*a;
		x2 = (-b-Math.sqrt(delta))/2*a;
		System.out.println("O valor de x1 é:"+x1);
		System.out.println("O valor de x2 é:"+x2);
	}

}
--------------------------------------------
package funcoes;

import java.util.Scanner;

public class func {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double num = sc.nextDouble();
		
		double quad = Math.pow(num, 2);
		double cubo = Math.pow(num, 3);
		double r2 = Math.sqrt(num);
		double r3 = Math.cbrt(num);
		
		System.out.println(quad);
		System.out.println(cubo);
		System.out.println(r2);
		System.out.println(r3);
			
	}

}
-------------------------------------------
package funcoes;

import java.util.Scanner;

public class condicionais {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Digite a nota 1:");
		double nota1 = sc.nextDouble();
		System.out.println("Digite a nota 2:");
		double nota2 = sc.nextDouble();
		System.out.println("Digite a nota 3:");
		double nota3 = sc.nextDouble();
		double media = (nota1*2)+(nota2*3)+(nota3*5)/10;
		if(media<5) {
			System.out.println("conceito E");
		}if(media>=5&&media<6) {
			System.out.println("Conceito D");
		}if(media>=6 && media<7) {
			System.out.println("Conceito C");
		}if(media>=7 && media<8) {
			System.out.println("Conceito B");
		}if(media>=8 && media<=10) {
			  System.out.println("Conceito A");
		}
		
	}
}
------------------------------------------
package funcoes;

import java.util.Scanner;

public class condicionais2 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Digite a nota 1:");
		double nota1 = sc.nextDouble();
		System.out.println("Digite a nota 2:");
		double nota2 = sc.nextDouble();
		System.out.println("Digite a nota 3:");
		double nota3 = sc.nextDouble();
		double media = (nota1 + nota2 + nota3) / 3;
		double mediaexame;
		if (media < 3) {
			System.out.println("reprovado");
		} else if (media < 5.9) {
			System.out.println("exame");
			mediaexame = 6 - media;
			System.out.println("É necessário tirar " + mediaexame + " para passar");
		} else {
			System.out.println("Aprovado");
		}

	}

}
------------------------------------------------
package funcoes;

import java.util.Scanner;

public class condicionais3 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double num1 = sc.nextDouble();
		double num2 = sc.nextDouble();
		if (num1 > num2) {
			System.out.println("O maior é: " + num1);
		} else if (num2 > num1) {
			System.out.println("O maior é:" + num2);
		}
	}

}
---------------------------------------------
