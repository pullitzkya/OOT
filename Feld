package OOT;

public class Feld {
	
	private FeldStatus status;
	
	/**
	 * Erstellt ein neues Feld
	 * @param f	Status des Feldes
	 */
	Feld(FeldStatus f){
			this.status = f; 
	}
	
	/**
	 * Setzt den Feldstatus
	 * @param Status der gesetzt werden soll
	 */
	public void setFeldStatus(FeldStatus f){
		this.status = f;
	}
	
	/**
	 * Liefert den aktuellen Status des Feldes
	 * @return	Status des Feldes
	 */
	public FeldStatus getFeldStatus(){
		return this.status;
	}
	
	/**
	 * Mögliche Zustände für ein Feld
	 */
	public enum FeldStatus{
			wasser("W"),
			schiff_spieler1("1"),
			schiff_spieler2("2");

		private final String print;

		private FeldStatus(String p){
			this.print = p;
		}

		public String toString(){
			return this.print;
		}

	}
	

	
}
