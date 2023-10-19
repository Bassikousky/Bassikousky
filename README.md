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


                System.out.println("Introduce una palabra: ");
        String palabra = scanner.nextLine();
        int i;
        for (i = 0; i < palabra.length(); i++) {
            System.out.println (palabra.charAt(i) + " en la posición " + (i+1));
        }

        System.out.println("Introduce una palabra: ");
        String palabra = scanner.nextLine();
        int i;
        for (i = palabra.length() - 1; i > -1; i--) {
            System.out.println (palabra.charAt(i) + " en la posición " + (i+1));
        }

// Francisco López Marín

import java.util.Scanner;

public class Main2 {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        int i = 0;
        int suma = 0;

        System.out.println("Introduce un número: ");
        int numero = scanner.nextInt();

        while (numero >= 0) {
            suma = suma + numero;
            i = i+1;
            System.out.println("Introduce un número: ");
            numero = scanner.nextInt();
        }
            
            System.out.println(suma/i);
    }
}

        System.out.println("Indica hasta que número irá la sucesión: ");
        int fin = scanner.nextInt();
        int a = 0;
        int b = 1;
        int c = 1;

        System.out.println(a);
        for (b = 1;c <= fin; b=c) {
            System.out.println(c);
            c = a+b;
            a = b;
        }
        final Scanner scanner = new Scanner(System.in);
        System.out.println("Indica hasta que número irá la sucesión: ");
        int fin = scanner.nextInt();
        int a = 0;
        int b = 1;
        int c = 0;


        System.out.println(a);
        System.out.println(b);
        while (c < fin) {
            c = a + b;
            if (c <= fin) {
                System.out.println(c);
            }
            a = b;
            b = c;
        }
    }
}

// Francisco López Marín

import java.util.Random;
import java.util.Scanner;

public class Main2 {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        final Random rand = new Random();
        final int numeroAleatorio = rand.nextInt(100);
        int i;
        int intento = -1;

        for (i=1;i!=11;i++) {
            System.out.println("Intento nº" + i);
            intento = scanner.nextInt();
            if (intento>numeroAleatorio){
                System.out.println("El numero es menor");
            }
            if (intento<numeroAleatorio){
                System.out.println("El numero es mayor");
            }
            if (i==10){
                System.out.println("FAIL!");
            }
            if (intento==numeroAleatorio){
                System.out.println("ENHORABUENA!");
                i=10;
            }
        }

// Francisco López Marín

import java.util.Random;
import java.util.Scanner;

public class Main2 {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        final Random rand = new Random();
        final int numeroAleatorio = rand.nextInt(100);
        int i = 1;
        int intento;
        boolean acierto = false;

        while (!acierto && i<11) {
            System.out.println("Intento nº" + i);
            intento = scanner.nextInt();
            i++;
            if (intento>numeroAleatorio){
                System.out.println("El numero es menor");
            }
            if (intento<numeroAleatorio){
                System.out.println("El numero es mayor");
            }
            if (intento==numeroAleatorio){
                System.out.println("ENHORABUENA!");
                acierto = true;
            }
            if (i==11) {
                System.out.println("FAIL!");

            }
        }

    }
}


import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        int i;
        int j;

        for (i=0;i<4;i++) {
            System.out.println("Semana "+(i+1));
            for (j=0;j<7;j++) {
                switch (j) {
                    case 0:
                        System.out.println("   \033[31m Lunes\u001B[0m");
                        break;
                    case 1:
                        System.out.println("    Martes");
                        break;
                    case 2:
                        System.out.println("    Miercoles");
                        break;
                    case 3:
                        System.out.println("    Jueves");
                        break;
                    case 4:
                        System.out.println("    Viernes");
                        break;
                    case 5:
                        System.out.println("    \033[32mSábado");
                        break;
                    case 6:
                        System.out.println("    Domingo\u001B[0m");
                        break;

                }

            }

        }



    }
}

import java.util.Scanner;

public class Main2 {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        int i;
        double suma;
        System.out.println("Introduce el número de alumnos");
        int alumno = scanner.nextInt();
        double nota;
        int j;
        String nombreAlumno;

        for (j = 0; j < alumno; j++) {
            suma = 0;
            i=0;
            System.out.println("Introduce el nombre del alumno: ");
            nombreAlumno = scanner.next();
            System.out.println("Introduce una nota: ");
            nota = scanner.nextInt();

            while (nota >= 0) {
                suma = suma + nota;
                i = i + 1;
                System.out.println("Introduce una nota: ");
                nota = scanner.nextInt();
            }
            System.out.println("El alumno " + nombreAlumno + " tiene una nota media de: ");
            System.out.println(suma / i);
        }
    }
}
//Francisco López Marín
import java.util.Scanner;

public class Main2 {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        int i; //numero de notas
        int j; //numero de alumno
        double suma;
        double nota;
        String nombreAlumno;
        System.out.println("Introduce el número de alumnos");
            int alumno = scanner.nextInt(); //número de alumnos total

        for (j = 0; j < alumno; j++) {
            suma = 0;
            i = 0;
            System.out.println("Introduce el nombre del alumno: ");
                nombreAlumno = scanner.next();
            System.out.println("Introduce las notas: ");
                nota = scanner.nextInt();

            while (nota >= 0) {
                suma = suma + nota;
                i = i + 1;
                nota = scanner.nextInt();
            }
            System.out.println("El alumno " + nombreAlumno + " tiene una nota media de: ");
            System.out.println(suma / i);
        }
    }
}


import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        int i;
        int j;
        System.out.println("Hasta que número quieres llegar?");
        int num = scanner.nextInt();

        for (i=0;i<=num;i++){
            System.out.println(i);

                for (j=0;j<=i;j++) {
                    if (i != num) {
                        System.out.print(j + " ");
                    }
                }
            }



    }
}

import java.util.Scanner;

public class Main3 {
    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        System.out.println("Indica el número al que quieres hacer el factorial:");
        int num = scanner.nextInt();
        int i;
        long prod = 1;

        for (i = 1; i <= num; i++) {
            prod = prod * i;
        }
        if (prod <= 0) {
            System.out.println("El numero es demasiado grande, eso dijo ella");
        } else {
            System.out.println("El factorial de " + num + " es " + prod);
        }
    }
}


import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        int i;
        int j;
        System.out.println("Hasta que número quieres llegar?");
        int num = scanner.nextInt();

        for (i = num; i >= 0; i--) {
            for (j = 0; j <= i; j++) {
                if (j != i) {
                    System.out.print(j + " ");
                }
            }
            if (i!=0){
                System.out.println(i);
            }
        }

            for (i = 0; i <= num; i++) {
                System.out.println(i);
                for (j = 0; j <= i; j++) {
                    if (i != num) {
                        System.out.print(j + " ");
                    }
                }
            }


        }
    }


// Francisco López Marín

import java.util.Scanner;

public class Main3 {

    public static String numchar(String palabra, char caracter) {

        char letra;
        int i = 0;
        int contador = 0;
        String textoFinal;

        while (i != palabra.length()) {
            letra = palabra.charAt(i);
            if (letra == caracter) {
                contador = contador + 1;
            }
            i++;
        }
        if (contador == 1) {
            textoFinal = "El carácter se repite una vez";
        } else if (contador == 0) {
            textoFinal = "El carácter no se encuentra en la palabra";
        } else {
            textoFinal = "El carácter se repite " + contador + " veces";
        }

        return textoFinal;
    }

    public static boolean vocalOConsonante(char caracter) {
        boolean letra;

        switch (caracter) {
            case 'a':
                letra = true;
                break;
            case 'e':
                letra = true;
                break;
            case 'i':
                letra = true;
                break;
            case 'o':
                letra = true;
                break;
            case 'u':
                letra = true;
                break;
            default:
                letra = false;
        }
        return letra;
    }

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);
        String palabra;
        char caracter;


        System.out.println("Introduce una palabra");
        palabra = scanner.next();

        while (!palabra.equals("exit")) {
            System.out.println("Introduce un carácter");
            caracter = scanner.next().charAt(0);

            String a = numchar(palabra, caracter);
            System.out.println(a);
            boolean b = vocalOConsonante(caracter);
            String vocal = (b) ? "La letra es vocal" : "La letra es consonante";
            System.out.println(vocal);

            System.out.println("Introduce una palabra");
            palabra = scanner.next();

        }
    }
}
