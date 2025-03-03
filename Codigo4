package com.generation;
import java.util.Scanner; //importamos el paquete scanner

public class Codigo4 {

	public static void main(String[] args) {
		Scanner s = new Scanner(System.in); //agregamos System.in para indicar que se ingresara texto por el usuario
	    System.out.print("Turno del jugador 1 (introduzca piedra, papel o tijeras): ");
	    String j1 = s.nextLine(); //
	    
	    

	    System.out.print("Turno del jugador 2 (introduzca piedra, papel o tijeras): "); //jugador número 2
	    Scanner s2 = new Scanner(System.in); //agregamos System.in para indicar que se ingresara texto por el usuario
	    String j2 = s2.nextLine(); //obtenemos el valor del j2 del scanner

	    s.close();
	    s2.close();


	    
	    if (j1.equals(j2)) {
	      System.out.println("Empate"); //decimos al usuario que hay empate si eligen la misma cadena
	    } else {
	      int g = 2;
	      switch(j1) { //con el switch comparamos los valores que da el jugador 1 respecto a los que llegue a ingresar el jugador 2, se asigna g=1 cuando el jugador 1 gana
	        case "piedra":
	          if (j2.equals("tijeras")) { //usamos metodo equals para comparar cadenas
	            g = 1;
	          }

	        case "papel":
	          if (j2.equals("piedra")) { //usamos metodo equals para comparar cadenas
	            g = 1;
	          }
	        case "tijera":
	          if (j2.equals("papel")) { //usamos metodo equals para comparar cadenas
	            g = 1;
	          }
	          break;
	        default:
	        g=2; //se asigna g=2 cuando el jugador 2 gana

	      }
	      System.out.println("Gana el jugador " + g);
	    }

	}

}
