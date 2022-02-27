# project.github.io
package Arraylist;

import java.util.ArrayList;

public class treipetrei {
	public static void main(String[] args) {
		ArrayList<ArrayList<String>> listaCumparaturi = new ArrayList();

		ArrayList<String> listaFructe = new ArrayList();
		listaFructe.add("mere");
		listaFructe.add("pere");
		listaFructe.add("pepene");

		ArrayList<String> listaLegume = new ArrayList();
		listaLegume.add("dovlecel");
		listaLegume.add("vinete");
		listaLegume.add("ardei iute");

		ArrayList<String> listaBauturiAlcoolice = new ArrayList();
		listaBauturiAlcoolice.add("Vodka");
		listaBauturiAlcoolice.add("Vin alb dulce");
		listaBauturiAlcoolice.add("Rom");

		listaCumparaturi.add(listaFructe);
		listaCumparaturi.add(listaLegume);
		listaCumparaturi.add(listaBauturiAlcoolice);
		for (int i = 0; i < listaCumparaturi.size(); i++) {
			System.out.println(listaCumparaturi.get(i));
		}
	}
}
                                                
