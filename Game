package OOT;

import OOT.Feld.FeldStatus;
import java.util.LinkedList;

public class Game {
	
	public LinkedList<Spieler> spieler = new LinkedList<Spieler>();
	
	public static int parseInput(String input) {
		int zeile = Character.getNumericValue(input.charAt(2));
		int spalte = Character.getNumericValue(input.charAt(3));
		return (zeile*10)+spalte;
	}
	
	public static boolean isValid(String input){
		if(input.matches("E[123]\\d\\d")){
			return true;
		}else{
			return false;
		}
	}
	
	
	public static void main(String[] args){
		System.out.println(isValid("E322"));
	}
	
	public boolean isRunning(){
		for(Spieler s : this.spieler){
			
		}
		return true;
	}
	
	
}
