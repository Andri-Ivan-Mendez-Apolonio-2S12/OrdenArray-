# OrdenArray-
Practica
import java.util.*;

public class Main {
    public static void main(String[] args){
        int [] numeros = {1,2,3,4,5,6,7,8,9,10};
 Arrays.sort(numeros);
 for (int i = numeros.length-1; i >= 0; i--) {
 System.out.println(""+numeros[i]);
 }
    }   
}
