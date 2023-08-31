Como os argumentos funcionam

                                                       Passando argumentos para o programa
O que vamos fazer

.Como passar argumentos para o programa
.compilar
.Executar
.Entender o que acontece

Os argumentos são os args que fica nos códigos

EX: public static void main(String[] args) {
O args é um arrey ou seja uma coleção de Strings a gente pode acessar qualquer possição da String.

Argumentos1

package com.madu.argumentos1.teste;

public class Argumentos1Teste {

	public static void main(String[] args) {
	
		System.out.println("Você digitou: " + args[0]);
		
	}

}


Argumentos2

package com.madu.argumentos;

public class Argumentos2 {

	public static void main(String[] args){
		
		System.out.println("Olá Mundo " + args[0]);
	}
	
}
