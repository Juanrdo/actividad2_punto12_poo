# actividad2_punto12_poo
package ecuaciongrado2;

import java.util.Scanner;

public class Ecuaciongrado2 {

    public static void main(String[] args) {
        double  a,b,c,x1,x2;
        
        Scanner ingresotecl = new Scanner (System.in);
       
        System.out.println("Ingrese el parametro A: ");
        a = ingresotecl.nextDouble();
        
        System.out.println("Ingrese el parametro B: ");
        b = ingresotecl.nextDouble();
        
        System.out.println("Ingrese el parametro C: ");
        c = ingresotecl.nextDouble();
        
        x1=(-b + (Math.sqrt(Math.pow(b, 2)-(4*a*c))))/(2*a);
        x2=(-b - (Math.sqrt(Math.pow(b, 2)-4*a*c)))/(2*a);
        
        System.out.println("las posibles soluciones son: "+ x1 +" y "+ x2);
        
        
        
        
    }
    
}
