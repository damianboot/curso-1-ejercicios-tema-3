# curso-1-ejercicios-tema-4

CONDICIONALES

public class Main {
    public static void main(String[] args) {
        int numero = 4;
        if (numero > 0) {
            System.out.println("Es positivo");
        } else if (numero < 0) {
            System.out.println("Es negativo");
        } else {
            System.out.println("Es 0");
        }
    }
}

---------------------------------------

WHILE

public class Main {
    public static void main(String[] args) {
            int numero = 3;

            while (numero <= 10) {
                System.out.println(numero);
                numero ++;
            }
        }
    }

---------------------------------------

DOWHILE

public class Main {
    public static void main(String[] args) {
            int numero = 11;

             do {
                System.out.println(numero);
                numero ++;
            } while (numero <= 10);
      }
}

--------------------------------------

FOR

public class Main {
        public static void main(String[] args) {
            for (int numero = 0; numero <= 3; numero++) {
                System.out.println(numero);
            }
        }
    }

---------------------------------------

SWICH

public class Main {
    public static void main(String[] args) {
        var estacion = "VERANO";

        switch (estacion) {
            case "PRIMAVERA":
                System.out.println("Es primavera");
                break;
            case "VERANO":
                System.out.println("Es verano");
                break;
            case "OTOÑO":
                System.out.println("Es otoño");
                break;
            case "INVIERNO":
                System.out.println("Es invierno");
                break;
            default:
                System.out.println("No es ninguna estacion");
        }
    }
}
