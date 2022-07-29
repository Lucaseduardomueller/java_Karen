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
package funcoes;

import java.util.Scanner;

public class condicionais4 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Digite um numero:");
		int num1 = sc.nextInt();
		System.out.println("Digite um numero:");
		int num2 = sc.nextInt();
		System.out.println("Digite um numero:");
		int num3 = sc.nextInt();

		if (num1 < num2 && num1 < num3) {
			if (num2 < num3) {
				System.out.println(num1 + "," + num2 + "," + num3);
			} else {
				System.out.println(num1 + "," + num3 + "," + num2);
			}
		} else if (num2 < num1 && num2 < num3) {
			if (num1 < num3) {
				System.out.println(num2 + "," + num1 + "," + num3);
			} else {
				System.out.println(num2 + "," + num3 + "," + num1);
			}
		} else if (num3 < num2 && num3 < num1) {
			if (num1 < num2) {
				System.out.println(num3 + "," + num1 + "," + num2);
			} else {
				System.out.println(num3 + "," + num2 + "," + num1);
			}
		}
		sc.close();

	}

}
----------------------------------------------
package funcoes;

import java.util.Scanner;

public class condicionais5 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Digite numeros em ordem crescente:");
		int num1 = sc.nextInt();
		System.out.println("Digite numeros em ordem crescente:");
		int num2 = sc.nextInt();
		System.out.println("Digite numeros em ordem crescente:");
		int num3 = sc.nextInt();
		System.out.println("Digite um numero aleatório:");
		int num4 = sc.nextInt();

		if (num1 < num2 && num1 < num3 && num1<num4) {
			if (num2 < num3 && num2< num4) {
			} else {
				System.out.println(num1 + "," + num3 + "," + num2);
			}
		} else if (num2 < num1 && num2 < num3) {
			if (num1 < num3) {
				System.out.println(num2 + "," + num1 + "," + num3);
			} else {
				System.out.println(num2 + "," + num3 + "," + num1);
			}
		} else if (num3 < num2 && num3 < num1) {
			if (num1 < num2) {
				System.out.println(num3 + "," + num1 + "," + num2);
			} else {
				System.out.println(num3 + "," + num2 + "," + num1);
			}
		}
		sc.close();
	}

}
---------------------------------------------------------
package funcoes;

import java.util.Scanner;

public class condicionais6 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int num1;
		System.out.println("Digite um numero:");
		num1 = sc.nextInt();

		if (num1 % 2 == 0) {
			System.out.println("O número é par");
		}
		if (num1 % 2 == 1) {
			System.out.println("O número é impar");
		}
	}

}
----------------------------------------------------------
package funcoes;

import java.util.Scanner;

public class condicionais7 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double i;
		int a, b, c;
		System.out.println("Digite o numero i:");
		i = sc.nextDouble();
		System.out.println("Digite o numero a:");
		a = sc.nextInt();
		System.out.println("Digite o numero b:");
		b = sc.nextInt();
		System.out.println("Digite o numero c:");
		c = sc.nextInt();

		if (i == 1) {
			if (a < b && a < c) {
				if (b < c) {
					System.out.println(a + ", " + b + ", " + c);
				}
				if (c < b) {
					System.out.println(a + ", " + c + ", " + b);
				}
			}
			if (b < a && b < c) {
				if (a < c) {
					System.out.println(b + ", " + a + ", " + c);
				}
				if (c < a) {
					System.out.println(b + ", " + c + ", " + a);
				}
			}
			if (c < a && c < b) {
				if (a < b) {
					System.out.println(c + ", " + a + ", " + b);
				}
				if (b < a) {
					System.out.println(c + ", " + b + ", " + a);
				}
			}
		}
		if (i == 2) {
			if (a > b && a > c) {
				if (b > c) {
					System.out.println(a + ", " + b + ", " + c);
				}
				if (c > b) {
					System.out.println(a + ", " + c + ", " + b);
				}
			}
			if (b > a && b > c) {
				if (a > c) {
					System.out.println(b + ", " + a + ", " + c);
				}
				if (c > a) {
					System.out.println(b + ", " + c + ", " + a);
				}
			}
			if (c > a && c > b) {
				if (a > b) {
					System.out.println(c + ", " + a + ", " + b);
				}
				if (b > a) {
					System.out.println(c + ", " + b + ", " + a);
				}
			}
		}
		if (i == 3) {
			if (a < b && a < c) {
				if (b < c) {
					System.out.println(a + ", " + c + ", " + b);
				}
				if (c < b) {
					System.out.println(a + ", " + b + ", " + c);
				}
			}
			if (b < a && b < c) {
				if (a < c) {
					System.out.println(b + ", " + c + ", " + a);
				}
				if (c < a) {
					System.out.println(b + ", " + a + ", " + c);
				}
			}
			if (c < a && c < b) {
				if (a < b) {
					System.out.println(c + ", " + b + ", " + a);
				}
				if (b < a) {
					System.out.println(c + ", " + a + ", " + b);
				}
			}
		}

	}

}
--------------------------------------------------------
atividade if else
--------------------------------------------------------
import java.util.Scanner;

public class ex1 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int num;
		double x,y,res;
		System.out.println("Digite 1 para somar dois números ou 2 para raiz quadrada:");
		num = sc.nextInt();
		if(num == 1) {
			System.out.println("Digite dois números seguidos:");
			x = sc.nextDouble();
			y = sc.nextDouble();
			res = x+y;
			System.out.println("A soma é: "+res);
		}else if(num ==2){
			System.out.println("Digite um número");
			x = sc.nextDouble();
			res = Math.sqrt(x);
			System.out.println("A raiz quadrada de "+x+" é "+res);
		}else {
			System.out.println("Número invalido");
		}

	}

}
----------------------------------------------
import java.util.Scanner;

public class ex2 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int dia, mes, ano, hora,min;
		System.out.println("Digite o dia:");
		dia = sc.nextInt();
		System.out.println("Digite o mês");
		mes = sc.nextInt();
		System.out.println("Digite o ano:");
		ano = sc.nextInt();
		System.out.println("Digite a hora:");
		hora = sc.nextInt();
		System.out.println("Digite o minuto");
		min = sc.nextInt();
		if(mes == 1) {
			System.out.println(dia+" de janeiro de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 2) {
			System.out.println(dia+" de fevereiro de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 3) {
			System.out.println(dia+" de março de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 4) {
			System.out.println(dia+" de abril de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 5) {
			System.out.println(dia+" de maio de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 6) {
			System.out.println(dia+" de junho de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 7) {
			System.out.println(dia+" de julho de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 8) {
			System.out.println(dia+" de agosto de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 9) {
			System.out.println(dia+" de setembro de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 10) {
			System.out.println(dia+" de outubro de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 11) {
			System.out.println(dia+" de novembro de "+ano);
			System.out.println(hora+":"+min);
		}else if(mes == 12) {
			System.out.println(dia+" de dezembro de "+ano);
			System.out.println(hora+":"+min);
		}else {
			System.out.println("Mês invalido");
		}
	}

}
------------------------------------------
import java.util.Scanner;

public class ex3 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int dia, mes, ano;
		int dia2, mes2, ano2;
		System.out.println("Digite o dia:");
		dia = sc.nextInt();
		System.out.println("Digite o mês");
		mes = sc.nextInt();
		System.out.println("Digite o ano:");
		ano = sc.nextInt();
		
		System.out.println("Digite outro dia:");
		dia2 = sc.nextInt();
		System.out.println("Digite outro mês");
		mes2 = sc.nextInt();
		System.out.println("Digite outro ano:");
		ano2 = sc.nextInt();
		
		if(ano>ano2) {
			System.out.println(dia+"/"+mes+"/"+ano+" é maior do que "+dia2+"/"+mes2+"/"+ano2);
		}else if(ano2>ano){
			System.out.println(dia2+"/"+mes2+"/"+ano2+" é maior do que "+dia+"/"+mes+"/"+ano);
		}else {
			if(mes>mes2) {
				System.out.println(dia+"/"+mes+"/"+ano+" é maior do que "+dia2+"/"+mes2+"/"+ano2);
			}else if(mes2>mes) {
				System.out.println(dia2+"/"+mes2+"/"+ano2+" é maior do que "+dia+"/"+mes+"/"+ano);
			}else {
				if(dia>dia2) {
					System.out.println(dia+"/"+mes+"/"+ano+" é maior do que "+dia2+"/"+mes2+"/"+ano2);
				}else if(dia2>dia) {
					System.out.println(dia2+"/"+mes2+"/"+ano2+" é maior do que "+dia+"/"+mes+"/"+ano);
				}else {
					System.out.println("As datas são iguais");
				}
			}
		}

	}

}
-----------------------------------------------
import java.util.Scanner;

public class ex4 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int hora,min,hora2,min2,tempoh,tempom;
		
		System.out.println("Digite a hora do início do jogo:");
		hora = sc.nextInt();
		System.out.println("Digite o minuto do início do jogo");
		min = sc.nextInt();
		
		System.out.println("Digite a hora do término do jogo:");
		hora2 = sc.nextInt();
		System.out.println("Digite o minuto do término do jogo");
		min2 = sc.nextInt();
		
		tempoh = hora-hora2;
		tempom = min-min2;
		if(tempoh<24) {
			System.out.println("Você jogou por "+tempoh+" horas e "+tempom+" minutos");
		}else {
			System.out.println("Você passou de 24 horas jogando esse jogo :(");
		}

	}

}
----------------------------------------------
import java.util.Scanner;

public class ex5 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int cod;
		double sal,rea;
		System.out.println("Digite o código correspondente ao seu cargo:");
		System.out.println("1 - Escrituário"
				+ "\n2 - Secretário"
				+ "\n3  - Caixa"
				+ "\n4 - Gerente"
				+ "\n5 - Diretor");
		//1 - 50% 2 - 35% 3 - 20% 4 - 10% 5 - não tem aumento
		cod = sc.nextInt();
		System.out.println("Digite seu salário:");
		sal = sc.nextDouble();
		
		if(cod == 1) {
			rea = sal * 0.5;
			System.out.println("Seu aumento é de "+rea+
			"\nSeu novo salário é de "+(rea+sal));
		}else if(cod == 2) {
			rea = sal * 0.35;
			System.out.println("Seu aumento é de "+rea+
			"\nSeu novo salário é de "+(rea+sal));
		}else if(cod == 3) {
			rea = sal * 0.20;
			System.out.println("Seu aumento é de "+rea+
			"\nSeu novo salário é de "+(rea+sal));
		}else if(cod == 4) {
			rea = sal * 0.10;
			System.out.println("Seu aumento é de "+rea+
			"\nSeu novo salário é de "+(rea+sal));
		}else if(cod == 5) {
			System.out.println("Você n tem aumento"
					+ "\nSeu salário é de"+sal);
		}
		

	}

}
----------------------------------------------
import java.util.Scanner;

public class ex6 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Digite o código correspondente:");
		System.out.println("1 - Imposto"
				+ "\n2 - Novo Salário"
				+ "\n3 - Classificação");
		int cod = sc.nextInt();
		
		if(cod == 1) {
			System.out.println("Digite seu salário:");
			double sal = sc.nextDouble();
			
			if(sal<500) {
				double imposto = sal*0.05;
				System.out.println("O valor do imposto é de "+imposto);
			}else if(sal<=850) {
				double imposto = sal*0.1;
				System.out.println("O valor do imposto é de "+imposto);
			}else if(sal>850) {
				double imposto = sal*0.15;
				System.out.println("O valor do imposto é de "+imposto);
			}
			
		}else if(cod == 2) {
			System.out.println("Digite seu salário:");
			double sal = sc.nextDouble();
			
			if(sal<450) {
				double novosalario = sal+100;
				System.out.println("O valor do novo salário é de "+novosalario);
			}else if(sal<750) {
				double novosalario = sal+75;
				System.out.println("O valor do novo salário é de "+novosalario);
			}else if(sal>1500) {
				double novosalario = sal+50;
				System.out.println("O valor do novo salário é de "+novosalario);
			}else {
				double novosalario = sal+25;
				System.out.println("O valor do novo salário é de "+novosalario);
			}
			
		}else if(cod == 3) {
			System.out.println("Digite seu salário:");
			double sal = sc.nextDouble();
			
			if(sal<=700) {
				System.out.println("Você é mal remunerado");
			}else {
				System.out.println("Você é bem remunerado");
			}
		}

	}

}
--------------------------------------------
atividade Switch-case
--------------------------------------------
package excase;

		import java.util.Scanner;

		
		    	public class ex1 {

		    	    public static void main(String[] args) {
		    	        Scanner sc = new Scanner(System.in);
		    	        
		    	        int cod;
		    	        
		    	        System.out.println("Informe o c�digo do seu cargo:");
		    	        cod = sc.nextInt();
		    	        
		    	        switch(cod) {
		    	        case 1:
		    	            System.out.println("Escritur�rio:");
		    	            System.out.println("Informe o salario atual:");
		    	            double salarioAtual = sc.nextDouble();
		    	            System.out.println("Novo salario �:"+salarioAtual*0.50);
		    	            break;
		    	            
		    	        case 2:
		    	            System.out.println("Secretario:");
		    	            System.out.println("Informe o salario atual:");
		    	             salarioAtual = sc.nextDouble();
		    	            System.out.println("Novo salario �:"+salarioAtual*0.35);
		    	            break;
		    	            
		    	        case 3:
		    	            System.out.println("Caixa:");
		    	            System.out.println("Informe o salario atual:");
		    	             salarioAtual = sc.nextDouble();
		    	            System.out.println("Novo salario �:"+salarioAtual*0.20);
		    	            break;
		    	            
		    	        case 4:
		    	            System.out.println("Gerente:");
		    	            System.out.println("Informe o salario atual:");
		    	         salarioAtual = sc.nextDouble();
		    	            System.out.println("Novo salario �:"+salarioAtual*0.10);
		    	            break;
		    	            
		    	        case 5:
		    	            System.out.println("N�o tem aumento!");
		    	            break;
		    	            
		    	        default:
		    	            System.out.println("c�digo errado");
		    	            break;
		    	        }    
		    	        sc.close();
		    	        
		    	    }

		    	}
-----------------------------------------------------------
package excase;
import java.util.Scanner;

public class ex2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Scanner sc = new Scanner(System.in);
        
        int codProduto, codPais, pesoproduto;
        
        System.out.println("Digite o codigo do produto:");
        codProduto = sc.nextInt();
        
        switch(codProduto) {
        case 1:
            System.out.println("Pre�o por grama = 10");
            System.out.println("Pre�o total do produto em kg:R$10000");
            break;
        case 2:
            System.out.println("Pre�o por grama = 10");
            System.out.println("Pre�o total do produto em kg:R$10000");
            break;
        case 3:
            System.out.println("Pre�o por grama = 10");
            System.out.println("Pre�o total do produto em kg:R$10000");
            break;
        case 4:
            System.out.println("Pre�o por grama = 10");
            System.out.println("Pre�o total do produto em kg:R$10000");
            break;
        case 5:
            System.out.println("Pre�o por grama = 25");
            System.out.println("Pre�o total do produto em kg:R$25000");
            break;
        case 6:
            System.out.println("Pre�o por grama = 25");
            System.out.println("Pre�o total do produto em kg:R$25000");
            break;
        case 7:
            System.out.println("Pre�o por grama = 25");
            System.out.println("Pre�o total do produto em kg:R$25000");
            break;
        case 8:
            System.out.println("Pre�o por grama = 35");
            System.out.println("Pre�o total do produto em kg:R$35000");
            break;
        case 9:
            System.out.println("Pre�o por grama = 35");
            System.out.println("Pre�o total do produto em kg:R$35000");
            break;
        case 10:
            System.out.println("Pre�o por grama = 35");
            System.out.println("Pre�o total do produto em kg:R$35000");
            break;
        default:
            System.out.println("Codigo invalido!");
        }
        
        System.out.println("Informe peso do produto comprado em Kg");
        pesoproduto = sc.nextInt();
    
        
        System.out.println("Digite o codigo de origem do pais:");
        codPais = sc.nextInt();
        
        switch(codPais) {
        case 1:
            System.out.println("imposto de 0%");
            codPais = 0;
            break;
        case 2:
            System.out.println("Imposto de 15%");
            break;
        case 3:
            System.out.println("Imposto de 25%");
            break;
        default:
            System.out.println("Codigo invalido!");
        }
        
        System.out.println("");
        
        
        sc.close();
    }


	}
------------------------------------------------------
package excase;

		import java.util.Scanner;

		public class ex3 {

		    public static void main(String[] args) {
		        Scanner sc = new Scanner(System.in);
		        double criterioA;
		        double criterioB;
		        
		        System.out.println("Informe a quantidade de livros:");
		        int qtdLivros = sc.nextInt();
		        
		        criterioA = (0.25*qtdLivros+7.50);
		        criterioB = (0.50*qtdLivros+2.50);
		        
		        if (criterioA<criterioB) {
		            System.out.println("Melhor op��o � o crit�rio A. Valor = " + criterioA);
		        } else if (criterioB<criterioA)  {
		            System.out.println("Melhor op��o � o crit�rio B. Valor = " + criterioB);

		        }
		    }

		
	}
--------------------------------------------------
package excase;

		import java.util.Scanner;

		public class ex4 {

		    public static void main(String[] args) {
		        Scanner sc = new Scanner(System.in);

		        int formatoPagamento;
		        double valorCompra;
		        
		        System.out.println("Informe o formato de parcelamento: "
		                + "\n1 - Pagamento � vista com 15% de desconto."
		                + "\n2 - Pagamento com cheque pr�-datado para 30 dias - 10% de desconto."
		                + "\n3 - Pagamento parcelado em 6 vezes - n�o tem desconto."
		                + "\n4 - Pagamento parcelado em 12 vezes - 8% de acr�scimo. ");
		        formatoPagamento = sc.nextInt();
		        
		        switch (formatoPagamento) {
		        case 1: 
		            System.out.println("Pagamento � vista com 15% de desconto.");
		            System.out.println("Informe o valor da compra: ");
		            valorCompra = sc.nextDouble();
		            System.out.println("Valor com desconto: " + (valorCompra*0.15 - valorCompra));
		            break;
		        case 2:
		            System.out.println("Pagamento com cheque pr�-datado para 30 dias - 10% de desconto.");
		            System.out.println("Informe o valor da compra: ");
		            valorCompra = sc.nextDouble();
		            System.out.println("Valor com desconto: " + (valorCompra*0.1 - valorCompra));
		            break;
		        case 3:
		            System.out.println("Pagamento parcelado em 6 vezes - n�o tem desconto.");
		            System.out.println("Informe o valor da compra: ");
		            valorCompra = sc.nextDouble();
		            System.out.println("Sem desconto");
		            System.out.println("Valor da parcela: " + (valorCompra/6));
		            break;
		        case 4:
		            System.out.println("Pagamento parcelado em 12 vezes - 8% de acr�scimo.");
		            System.out.println("Informe o valor da compra: ");
		            valorCompra = sc.nextDouble();
		            System.out.println("Valor com acr�scimo: " + (valorCompra*0.08 + valorCompra));
		            System.out.println("Valor da parcela: " + (valorCompra*0.08 + valorCompra)/12 );
		            break;
		        }
		        
		    }

		
	}
-------------------------------------------------
atividade while
-------------------------------------------------
import java.util.Scanner;

public class ex_02 {

	public static void main(String[] args) {
		
	Scanner Sc = new Scanner(System.in);
	
	double num;
	
	System.out.println("Insira um n�mero: ");
	num = Sc.nextInt();
	
	while (num > 0) {
		
		System.out.println("\nN�mero: " + num + "\nQuadrado: " + Math.pow(num, 2) + "\nCubo: " + Math.pow(num, 3) + 
				"\nRaiz quadrada: " + Math.sqrt(num) + "\nInsira outro n�mero ou encerre com um valor menor ou igual a 0: ");
		num = Sc.nextInt();
	}
	
	Sc.close();
	}
	
	}
--------------------------------------------------------
import java.util.Scanner;

public class ex_03 {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        int num, i =0, qtdNum=0, somaNum = 0, par=0, mediaPar=0, impar=0, soma=0;
    
        int numMaior = 0;
        int numMenor = 0;

        do {
            System.out.println("Informe um n�mero: ");
            num = sc.nextInt();
            
            soma = soma +num;
            i = i + 1;
            
            if (num%2==0) {
                mediaPar = mediaPar +num;
                par++;
            }
            
            if (num<numMenor && num !=0) {
                numMenor = num;
            }
            
            if (num> numMaior) {
                numMaior = num;
            }
            
            if (num==0) {
                i--;
                par--;
            }
            
        } while (num<30.000);
        
        int media = soma/i;
        mediaPar = mediaPar/par;
        
        System.out.println("Soma: " + soma);
        System.out.println("Quantidade de n�meros digitados: " + i);
        System.out.println("Maior n�mero digitado: " + numMaior);
        System.out.println("Menor n�mero digitado: " + numMenor);
        System.out.println("M�dia dos n�meros pares: " + media); 
    }

}
-----------------------------------------------------------
import java.util.Scanner;

public class ex_04 {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        double salarioMinimo;
        double quilowatts;
        
        System.out.println("Tipo   | % DE ACR�SCIMO SOBRE O VALOR GASTO");
        System.out.println("1      |               5%");
        System.out.println("2      |              10%");
        System.out.println("3      |              15%");
        
            System.out.println("Digite o salario:");
            salarioMinimo = sc.nextInt();
            
            quilowatts = salarioMinimo/8;
            
            System.out.println("O valor do quilowatt:R$"+quilowatts);
            
            //residencial
            double residencial = salarioMinimo*0.05;
            System.out.println("O valor de acrescimo e:R$"+residencial);
            
            //comercial
            double comercial = salarioMinimo*0.10;
            System.out.println("O valor de acrescimo do comercial �:R$"+comercial);
            
            //industrial
            double industrial = salarioMinimo*0.15;
            System.out.println("O valor de acrescimo do industrial �:R$"+industrial);
            
            //faturamento geral
            double fatGeral = residencial + comercial + industrial;
            System.out.println("Faturamento geral da empresa:R$"+fatGeral);
            
            sc.close();
    }

}
-----------------------------------------------------
atividades for
-----------------------------------------------------
import java.util.Scanner;
public class ex_01 {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        int tabuada,x;
        
        System.out.println("Digite o numero da tabuada desejada:");
        tabuada = sc.nextInt();

        if(tabuada<0) {
            System.out.println("Numero invalido! Por favor reinicie o programa e use um numero valido!");
            System.exit(tabuada);
        }
        
        for(x=0;x<=10;x++) {
            System.out.println(tabuada+"x"+x+"="+tabuada*x);
        }
        sc.close();
    }

}
---------------------------------------------------
package forex;
import java.util.Scanner;


public class Ex_02 {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        
        double altura = 0, peso = 0, mediaAltura = 0, mediaIdade = 0, mediaIdadePeso = 0,quantAltura = 0;
        int x = 0, y = 0, quantIdadeInferior = 0, quantIdade = 0, idade;
        
        
        System.out.println("1) Digite o valor para x times: ");
        x = sc.nextInt();        
        System.out.println("2) Digite o valor para y jogadores: ");
        y = sc.nextInt();
            
            for(int i=1; i<=x; i++){
            for (int j = 1; j<=y; j++){ 
                System.out.println("3) Digite a idade do jogador " + "["+ j + "] do time " + "["+ i + "]");
                idade = sc.nextInt();
                System.out.println("4) Digite o peso do jogador " + "["+ j + "] do time " + "["+ i + "]");
                peso = sc.nextDouble();
                System.out.println("5) Digite a altura do jogador " + "["+ j + "] do time " + "["+ i + "]");
                altura = sc.nextDouble();
                    
        
        if(idade <=18 ){
            quantIdadeInferior++;
        }
        
    
        quantIdade = quantIdade + idade;
        mediaIdade = quantIdade/y;
        

        quantAltura = quantAltura + altura;
        mediaAltura = quantAltura/y;
        
        }
            System.out.println("\n>>> A média de jogadores com peso acima de 80: "+ mediaIdadePeso);        
            System.out.println("\n>>> A média de idades dos jogadores: "+ mediaIdade);
            System.out.println("\n>>> A média de alturas dos jogadores: "+ mediaAltura);        
            System.out.println("\n>>> A quantidade de jogadores de todos os times com idade inferior a 18 anos é: "+ quantIdadeInferior);
            
            sc.close();
    
        }
    }
        
        
        }
------------------------------------------------------
package forex;

import java.util.Scanner;

public class ex_03 {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        int numOperario, numPecas, sexoOperario;
        double salarioMinimo;
        
        System.out.println("Numero do operario:");
        numOperario = sc.nextInt();
        
        System.out.println("Numero de peÃ§as fabrica por mes:");
        numPecas = sc.nextInt();
        
        System.out.println("Sexo do operario:");
        sexoOperario = sc.nextInt();
        
        switch(numOperario) {
        case 1:
            System.out.println("Salario minimo:");
            salarioMinimo = sc.nextDouble();
            System.out.println("");
            
        case 2:
            System.out.println("Salario minimo:");
            salarioMinimo = sc.nextDouble();
            double salarioMinimo2 = salarioMinimo*0.03;
            System.out.println("Salario total:"+(salarioMinimo2 + salarioMinimo));
            
        case 3:
            System.out.println("Salario minimo:");
            salarioMinimo = sc.nextDouble();
            double salarioMinimo3 = salarioMinimo*0.05;
            System.out.println("Salario total:"+(salarioMinimo3 + salarioMinimo));
            
        default:
            System.out.println("Codigo invalido!");
        }
    
    }

}
------------------------------------------------------------------
atividade avaliativa
------------------------------------------------------------------
import java.util.Scanner;

public class questao2 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Informe um número ímpar: ");
        int num = sc.nextInt();
        while(num % 2 == 0){
            System.out.println("Número inválido, por favor, digite um número ímpar: ");
            num = sc.nextInt();
        }

        int acres = 0;
        int pri = 1;
        String asteriscos = "";
        double espInt = Math.floor(num / 2);
        String espacos = "";


        for(int i = 1; i <= num; i++){
            for(int e = 1; e <= espInt; e++){
                espacos += " ";
            }
            for(int j = 1; j <= (pri + acres); j++){
                asteriscos += "*";
            }

            if(i > (num / 2)){
                pri--;
                acres = pri - 1;
                espInt++;
            } else {
                espInt--;
                acres = pri;
                pri++;
            }


            asteriscos = espacos + asteriscos;
            System.out.println(asteriscos);
            asteriscos = "";
            espacos = "";
        }

    }
}
-------------------------------------------------------------------
import java.util.Scanner;

public class questao1 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        double result=0;

        System.out.print("---MENU DE OPÇÕES---" +
                "\n1 - Soma;" +
                "\n2 - Multiplicação;" +
                "\n3 - Divisão;" +
                "\n4 - Subtração;" +
                "\n5 - Potenciação;" +
                "\n6 - Porcentagem;" +
                "\n7 - Raiz quadrada;" +
                "\n-->  ");
        int opcao = sc.nextInt();

        switch(opcao){
            case 1: {
                System.out.print("Informe a quantidade de números que deseja somar:");
                int qntd = sc.nextInt();
                while(qntd < 2 || qntd > 5){
                    System.out.println("Número inválido, digite novamente (2-5)");
                    qntd = sc.nextInt();
                }
                for(int i = 1; i <= qntd; i++) {
                    System.out.println("Informe o número: " + i + ":");
                    result += sc.nextDouble();
                }
                break;
            }
            case 2: {
                System.out.print("Informe a quantidade de números que deseja multiplicar:");
                int qntd = sc.nextInt();
                while(qntd < 2 || qntd > 5){
                    System.out.println("Número inválido, digite novamente (2-5)");
                    qntd = sc.nextInt();
                }
                result = 1;
                for(int i = 1; i <= qntd; i++) {
                    System.out.println("Informe o número: " + i + ":");
                    result *= sc.nextDouble();
                }
                break;
            }
            case 3: {
                System.out.print("Informe 1 número:");
                double num1 = sc.nextDouble();
                System.out.print(num1 + " / :");
                double num2 = sc.nextDouble();

                result = num1 / num2;
                break;
            }
            case 4: {
                System.out.print("Informe a quantidade de números que deseja subtrair (2 - 5):");
                int qntd = sc.nextInt();
                while(qntd < 2 || qntd > 5){
                    System.out.println("Número inválido, digite novamente (2-5)");
                    qntd = sc.nextInt();
                }

                for(int i = 1; i <= qntd; i++) {
                    System.out.println("Informe o número: " + i + ":");
                    if(i == 1){
                        result = sc.nextDouble();
                    } else {
                        System.out.print(result + " - :");
                        result -= sc.nextDouble();
                    }
                }
                break;
            }
            case 5: {
                System.out.print("Informe 1 número:");
                double num1 = sc.nextDouble();
                System.out.print(num1 + " ^ :");
                double num2 = sc.nextDouble();

                result = Math.pow(num1, num2);
                break;
            }
            case 6: {
                System.out.print("Informe 1 número:");
                double num1 = sc.nextDouble();
                System.out.print(num1 + " % de :");
                double num2 = sc.nextDouble();

                result = (num1 * 100) / num2;
                break;
            }
            case 7: {
                System.out.print("Tirar a raiz quadrada de:");
                double num1 = sc.nextDouble();

                result = Math.sqrt(num1);
                break;
            }
        }

        System.out.println("Resultado da operação: " + result);

        sc.close();
    }
}
