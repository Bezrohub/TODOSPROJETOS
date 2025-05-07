package Luize;

import java.util.Scanner;

public class Classe {

	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		int escolha = 0;
		while(escolha != 6 ) {
		System.out.println("digite o primeiro número: ");
		int a = scanner.nextInt();
		System.out.println("digite o segundo número: ");
		int b = scanner.nextInt();
		System.out.println("1 – Soma");
		System.out.println("2 - Subtração");
		System.out.println("3 - Multiplicação");
		System.out.println("4 – Divisão");
		System.out.println("5 - Trocar Valores");
		System.out.println("6 - Sair");
		escolha = scanner.nextInt();
		switch (escolha) {
		case 1:
			soma(a, b);
			break;
		case 2:
			sub(a, b);
			break;
		case 3:
			multi(a, b);
			break;
		case 4:
			div(a, b);
			break;
		case 5:	
			break;
		case 6:
			break;
		default:
			System.out.println("opção inválida");
			break;
		}}
	}

//SOMAAAAAAAAAAA
	public static void soma(int a, int b) {
		int c;
		c = a + b;
		System.out.println("Soma: " + c);
	}

// SUBTRAÇÃOOOOOO
	public static void sub(int a, int b) {
		int c;
		c = a - b;
		System.out.println("Subtração: " + c);
	}

//MULTIPLICAÇAOOOOO
	public static void multi(int a, int b) {
		int c;
		c = a * b;
		System.out.println("Multiplicação: " + c);
	}

//DIVISÃÃOOOOOOO
	public static void div(int a, int b) {
		int c;
		c = a / b;
		System.out.println("Divisão: " + c);
	}}
