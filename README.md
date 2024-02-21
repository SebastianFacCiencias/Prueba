### PruebaPunto
Código de la práctica 01.
...
public class PruebaPunto {

	public static void main(String[] args) {
		Punto p2 = new Punto(4, 7);
		Punto p3 = new Punto(-2.4,1.7); 
		Punto p4 = new Punto(3, 5.5);
		
		Punto p5 = new Punto(6.8, -1.7);
		Punto p6 = new Punto(-3, 4.5);
		Punto p7 = new Punto(-8.7, -6.4);
		
		Punto p8 = new Punto(1,-6);
		Punto p9 = new Punto(1,4);
		Punto p10 = new Punto(-9,-6);
		Punto p11 = new Punto(-9,4);
		
		//Primer ejercicio
		boolean x = p4.estanAlineados(p2, p3);
		System.out.println("No estan alineados " + x );
		
		//Segundo ejercicio
		double y = p5.distancia(p6);
		double r = p5.distancia(p7);
		double q = (y * r)/2;
		
		System.out.println("El area del rectángulo es: "+ q);
		
		//Terer ejercicio
		double z = p11.distancia(p8);
		double u = p8.distancia(p9);
		double h = p9.distancia(p10);
		double j = p10.distancia(p11);
		double f = z + u + h + j;
		
		System.out.println("El perímetro del rectángulo es: "+ f);
	}

}
...


