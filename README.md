- 👋 Hi, I’m @Bassikousky
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Bassikousky/Bassikousky is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import java.util.Scanner;

public class Main {


    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);

        System.out.println("Indica el primer valor");
        String x = scanner.nextLine();
        System.out.println("Indica el segundo valor");
        String y = scanner.nextLine();
        int z= 1;
        int a=0;
        z += a;

        System.out.println("El resultado de " + x + " y " + y + " es: " + z);
    }

}

        String x="Hola";
        int z = x.length();

       for (int i=z-1; i >=0; i--)
        System.out.println(x.charAt(i));


        
import java.util.Scanner;

public class Main2 {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);

        String x="Hola";
        System.out.println("Introduce el caracter");
        String y = scanner.nextLine();
        int w = x.indexOf(y);

        if (w != -1) {
            System.out.println("El caracter está en la posición: " + (w+1));
        }
        else{
            System.out.println("El caracter no está en la palabra");
        }
    }
    }


import java.util.Scanner;

public class Main2 {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);

        System.out.println("Introduce el DNI");
        String x= scanner.nextLine();
        String y = x.trim();
        int z = y.length();

        String q = z == 9 ? "Validación OK" : "Validación KO";
        System.out.println(q);

        if (z >= 9) {
            System.out.println("El espacio está en la posición: " + (y.indexOf(" ")+1));

        }



    }
    }


            final Scanner scanner = new Scanner(System.in);

        System.out.println("Introduce el DNI");
        String x = scanner.nextLine();
        String y = x.trim();
        int z = y.length();

        String q = z == 9 ? "Validación OK" : "Validación KO";
        System.out.println(q);

        if (z == 10) y.equals(y.indexOf(" ") != -1); {
                System.out.println("El espacio está en la posición: " + y.indexOf(" "));
                System.out.println("El DNI es: ");
                System.out.println(y.substring(0, y.indexOf(" ")) + y.substring((y.indexOf(" ") + 1), y.length()));
                System.out.println("Validación OK");




import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);

        System.out.println("Introduce el primer número: ");
        int x = scanner.nextInt();
        System.out.println("Introduce el segundo número: ");
        int y = scanner.nextInt();
        System.out.println("Introduce el tercer número: ");
        int z = scanner.nextInt();

        if ((x>y) && (x>z)) {
            System.out.println("El número mayor es: ");
            System.out.println(x);
        } else if ((y>x) && (y>z)) {
            System.out.println("El número mayor es: ");
            System.out.println(y);
        } else {
            System.out.println("El número mayor es: ");
            System.out.println(z);
        }
    }
}


import java.util.Scanner;

public class Main2 {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);

        System.out.println("Introduce el día de la semana: ");
        String dia = scanner.nextLine();
        String dia_minus = dia.toLowerCase();

        switch (dia_minus) {
            case "lunes":
                System.out.println("Hoy es " + dia_minus +", el dia 1 de la semana");
                break;
            case "martes":
                System.out.println("Hoy es " + dia_minus +", el dia 2 de la semana");
                break;
            case "miercoles":
                System.out.println("Hoy es " + dia_minus +", el dia 3 de la semana");
                break;
            case "jueves":
                System.out.println("Hoy es " + dia_minus +", el dia 4 de la semana");
                break;
            case "viernes":
                System.out.println("Hoy es " + dia_minus +", el dia 5 de la semana");
                break;
            case "sábado":
                System.out.println("Hoy es " + dia_minus +", el dia 6 de la semana");
                break;
            case "sabado":
                System.out.println("Hoy es " + dia_minus +", el dia 6 de la semana, pero has olvidado la tilde");
                break;
            case "domingo":
                System.out.println("Hoy es " + dia_minus +", el dia 7 de la semana");
                break;
            default:
                System.out.println("No has introducido un día correcto");


        }

    }
}


import java.sql.SQLOutput;
import java.util.Scanner;

public class Main2 {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);

        System.out.println("Introduce tu edad: ");
        int edad = scanner.nextInt();

        if (edad >= 18) {
            System.out.println("Introduce tu provincia: ");
            String provincia = scanner.next();

            switch (provincia) {
                case "Sevilla":
                    System.out.println("El codigo de provincia es 41");
                    break;
                case "Huelva":
                    System.out.println("El codigo de provincia es 21");
                    break;
                case "Cádiz":
                    System.out.println("El codigo de provincia es 11");
                    break;
                case "Málaga":
                    System.out.println("El codigo de provincia es 29");
                    break;
                case "Córdoba":
                    System.out.println("El codigo de provincia es 14");
                    break;
                case "Granada":
                    System.out.println("El codigo de provincia es 18");
                    break;
                case "Jaen":
                    System.out.println("El codigo de provincia es 23");
                    break;
                case "Almería":
                    System.out.println("El codigo de provincia es 04");
                    break;
                default:
                    System.out.println("No has introducido una provincia válida");
                    
            }
        } else {
            System.out.println("No eres mayor de edad");
        }


        }

    }

            System.out.println("Introduce un código postal: ");
        String cp = scanner.nextLine();

        while (cp.length() != 5) {
            System.out.println("Introduce un código postal válido: ");
            cp = scanner.nextLine();
        }

        System.out.println("Codigo postal correcto");

        final Scanner scanner = new Scanner(System.in);
        String cp = "a";

        do {
            System.out.println("Introduce un código postal válido: ");
            cp = scanner.nextLine();
        } while (cp.length() != 5);
