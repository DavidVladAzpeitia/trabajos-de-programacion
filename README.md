import java.util.Scanner;

public class ejercicio4 {
    public static void main(String[] args){
        Scanner numero = new Scanner(System.in);

        int edadMinima = 18;

        String edad;

        final double precio = 7;

        System.out.println(" dime tu edad");

        edad = numero.nextLine(); 

        double edadDecimal = Double.parseDouble(edad);

        System.out.println("tu edad es(string): " + edad);
      System.out.println(" tu edad es(numero): " + edadDecimal);

        if (edadDecimal <= edadMinima) {
         System.out.println("eres mayor de edad: " + false);
    
}else System.out.println("eres mayor de edad: " + true);

System.out.println("el precio de la entrada es: " + precio + "$");






}
}
