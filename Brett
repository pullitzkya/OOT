package OOT;

import java.util.LinkedList;

import OOT.Feld.FeldStatus;


public class Brett {
	
	private LinkedList<Feld> felder = new LinkedList<Feld>();
	
	/**
	 * Erstellt ein neues, leeres 10x10 Brett (Wasser)
	 */
	public Brett(){
		for(int i = 0; i < 100; i++){
			this.felder.add(new Feld(Feld.FeldStatus.wasser));
		}
	}
	
	/**
	 * Liefert den Status eines Feldes
	 * @param fNr	Nummer des Feldes
	 * @return Felstatus
	 */
	public FeldStatus getFeldStatus(int fNr){
		return this.felder.get(fNr).getFeldStatus();
	}
	
	/**
	 * Setzt einen neuen Status für ein FEld
	 * @param fNr	Nummer des Feldes
	 * @param fs	Status
	 */
	public void setFeld(int fNr, FeldStatus fStatus){
		this.felder.get(fNr).setFeldStatus(fStatus);
	}
	
	/**
	 * Ausgabe von Brett auf Konsole
	 */
	public void printBrett(){
		
		System.out.println("---------------------");
		
		int current = 0;
		
		for(int i = 0; i<100; i++){
			
			System.out.print("|" + this.felder.get(current).getFeldStatus().toString());

			current++;
			if(current%10==0){
				System.out.print("|\n");
			}
		}
		
		System.out.println("---------------------");
		
	}
	
	
}

	
