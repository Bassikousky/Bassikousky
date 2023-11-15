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


import java.util.Scanner;

public class Coche {
    private int tamanoDeposito;
    private int cantidadGasolina;
    private int kilometrosRecorridos;

    public Coche(final int tamanoDeposito, final int gasolinaInicial) {
        this.tamanoDeposito = tamanoDeposito;
        if (gasolinaInicial > this.tamanoDeposito) {
            this.cantidadGasolina = tamanoDeposito;
        } else {
            cantidadGasolina = gasolinaInicial;
        }
        this.kilometrosRecorridos = 0;
    }

    public boolean andar() {
        if (this.cantidadGasolina > 0) {
            System.out.print("=");
            this.cantidadGasolina--;
            this.kilometrosRecorridos++;
            return true;
        } else {
            System.out.print("[PARA EN= " + this.kilometrosRecorridos + "]");
            return false;
        }
    }

    public void echarGasolina(int cantidadGasolina) {
        if (this.cantidadGasolina + cantidadGasolina > tamanoDeposito) {
            this.cantidadGasolina = tamanoDeposito;
        } else {
            this.cantidadGasolina += cantidadGasolina;
        }
        System.out.print("(GAS=" + cantidadGasolina + ")");
    }

    public int pintarKilometros() {
        return kilometrosRecorridos;
    }

    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);

        System.out.println("Indica el tamaño de depósito");
        int deposito = scanner.nextInt();
        System.out.println("Indica la cantidad de gasolina");
        int gaso = scanner.nextInt();
        System.out.println("Indica los km a recorrer");
        int km = scanner.nextInt();

        Coche coche1 = new Coche(deposito, gaso);


        while (km > coche1.kilometrosRecorridos) {
            if (!coche1.andar()) {
                System.out.println("Indica la cantidad de gasolina");
                int x = scanner.nextInt();
                coche1.echarGasolina(x);
            }
            System.out.println(coche1.pintarKilometros());
        }
        System.out.println("HAS LLEGADO!");
    }
}

public abstract class Vaso {

    private int cantidad;
    private int cantidadInicial;

    public Vaso(final int cantidad) {
        this.cantidad = 0;
        this.cantidadInicial = cantidad;
    }

    public int getCantidad() {
        return cantidad;
    }

    public void llenar() {
        this.cantidad = cantidadInicial;
        System.out.println("Llenando el vaso " + this.cantidadInicial);
    }

    public void vaciar() {
        this.cantidad = 0;
        System.out.println("Vaciando el vaso " + this.cantidadInicial);
    }

    private int getCantidadInicial() {
        return this.cantidadInicial;
    }

    public void rellenarCon(final Vaso vaso) {
        System.out.println("Vertiendo vaso " + vaso.getCantidadInicial() + " en vaso " + this.cantidadInicial);
        int cantidadExtra = vaso.getCantidad();
        if (cantidadExtra + this.cantidad > this.cantidadInicial) {
            int cantidadVertida = this.cantidadInicial - cantidad;
            vaso.setCantidad(cantidadExtra - cantidadVertida);
            this.cantidad = cantidadInicial;
        } else {
            vaso.vaciar();
            this.cantidad += cantidadExtra;
        }
    }

    private void setCantidad(int cantidad) {
        this.cantidad = cantidad;
    }


    public static void main(String[] args) {
        Vaso3 vaso3 = new Vaso3();
        Vaso5 vaso5 = new Vaso5();

        vaso5.llenar();
        vaso3.rellenarCon(vaso5);
        System.out.println("El vaso 5 tiene: "+vaso5.getCantidad());
        vaso3.vaciar();
        vaso3.rellenarCon(vaso5);
        System.out.println("El vaso 3 tiene: "+vaso3.getCantidad());
        vaso5.llenar();
        vaso3.rellenarCon(vaso5);
        System.out.println("El vaso 5 tiene: "+vaso5.getCantidad());
    }
}

// Francisco López Marín

import com.iesfuengirola1.juegos.*;
import java.util.Scanner;

public class Main {
    public static void main(final String[] args) {
        Juego juego = new Juego();
        Scanner scanner = new Scanner(System.in);

        Granjero granjero = new Granjero();
        Lobo lobo = new Lobo();
        Col col = new Col();
        Cabra cabra = new Cabra();

        juego.introducirPersonaje(granjero);
        juego.introducirPersonaje(lobo);
        juego.introducirPersonaje(col);
        juego.introducirPersonaje(cabra);

        String pj;
        String mov;

        juego.comenzar();
        System.out.println("Comenzar aqui");


        while (!juego.haGanado() && !juego.haPerdido()) {
            System.out.println("Di el personaje a mover");
            pj = scanner.next();
            System.out.println("Di hacia donde (i para izquierda, d para derecha )");
            mov = scanner.next();
            switch (pj) {
                case "lobo":
                    if (mov.equals("i")) {
                        lobo.moverIzquierda();
                    } else {
                        lobo.moverDerecha();
                    }
                    break;
                case "cabra":
                    if (mov.equals("i")) {
                        cabra.moverIzquierda();
                    } else {
                        cabra.moverDerecha();
                    }
                    break;
                case "col":
                    if (mov.equals("i")) {
                        col.moverIzquierda();
                    } else {
                        col.moverDerecha();
                    }
                    break;
                default:
                    if (mov.equals("i")) {
                        granjero.moverIzquierda();
                    } else {
                        granjero.moverDerecha();
                    }
                    break;
            }
        }
    }
}

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        final Scanner scanner = new Scanner(System.in);

        System.out.println("Introduce una palabra");
        String palabra1 = scanner.next();
        System.out.println("Introduce una palabra");
        String palabra2 = scanner.next();
        System.out.println("Introduce un carácter");
        char caracter = scanner.next().charAt(0);

        char letra;
        int i = 0;
        int contador1 = 0;
        int contador2 = 0;

        while (i != palabra1.length()) {
            letra = palabra1.charAt(i);
            if (letra == caracter) {
                contador1 = contador1 + 1;
            }
            i++;
        }
        System.out.println(palabra1 + " tiene " + contador1 + " " + caracter);

        i = 0;
        while (i != palabra2.length()) {
            letra = palabra2.charAt(i);
            if (letra == caracter) {
                contador2 = contador2 + 1;
            }
            i++;
        }
        System.out.println(palabra2 + " tiene " + contador2 + " " + caracter);

        if (contador1 > contador2) {
            System.out.println("En " + palabra1 + " está mas veces la letra " + caracter + " que en " + palabra2);
        } else if (contador2 > contador1) {
            System.out.println("En " + palabra2 + " está mas veces la letra " + caracter + " que en " + palabra1);
        } else {
            System.out.println("En " + palabra2 + " está presente las mismas veces la letra " + caracter + " que en " + palabra1);
        }
    }
}

import java.time.DayOfWeek;
import java.time.LocalDate;
import java.time.LocalDateTime;
import java.time.LocalTime;
import java.time.temporal.TemporalAdjusters;

public class Main {
    public static void main(String[] args) {



        LocalDate dia = LocalDate.now();
        System.out.println(dia);
        LocalDate dia2 = dia.plusDays(200);
        System.out.println(dia2);
        LocalTime hora = LocalTime.now();
        System.out.println(hora);
        LocalDate otroDia = LocalDate.of(2022,10,10);
        System.out.println(otroDia);
        LocalTime otraHora = LocalTime.of(14,55,5);
        System.out.println(otraHora);
        LocalDateTime fechaYhora = LocalDateTime.now();
        System.out.println(fechaYhora);
        LocalDateTime otraFechayHora = LocalDateTime.of(2002,8,24,19,34);
        System.out.println(otraFechayHora);

        DayOfWeek diaSemana = LocalDate.now().with(TemporalAdjusters.firstDayOfNextMonth()).getDayOfWeek();



    }
}

import java.time.DayOfWeek;
import java.time.LocalDate;
import java.time.LocalDateTime;
import java.time.LocalTime;
import java.time.temporal.TemporalAdjusters;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Indique un año");
        int año = scanner.nextInt();
        System.out.println("Indique un mes");
        int mes = scanner.nextInt();
        System.out.println("Indique un día");
        int dia = scanner.nextInt();

        LocalDate fecha = LocalDate.of(año,mes,dia);
        System.out.println(fecha);

        System.out.println("Indique que dato quiere modificar");
        String variable = scanner.next();

        System.out.println("Indique cuanto quiere sumar");
        int suma = scanner.nextInt();
        LocalDate nuevaFecha = LocalDate.now();

        switch (variable) {
            case "año":
                nuevaFecha = fecha.plusYears(suma);
            break;
            case "mes":
                nuevaFecha = fecha.plusMonths(suma);
            break;
            case "dia":
                nuevaFecha = fecha.plusDays(suma);
            break;
        }

        System.out.println(nuevaFecha);


    }
}

import java.time.LocalDate;
import java.util.Scanner;

public class Main2 {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Indique la fecha con barras");
        String fecha1 = scanner.next();
        String fechaLimpia = fecha1.replace("/","");
        String diaFecha = fechaLimpia.substring(0,2);
        String mesFecha = fechaLimpia.substring(2,4);
        String añoFecha = fechaLimpia.substring(4,8);
        int dia = Integer.parseInt(diaFecha);
        int mes = Integer.parseInt(mesFecha);
        int año = Integer.parseInt(añoFecha);


        LocalDate fecha = LocalDate.of(año,mes,dia);
        System.out.println(fecha);

        System.out.println("Indique que dato quiere modificar");
        String variable = scanner.next();

        System.out.println("Indique cuanto quiere sumar");
        int suma = scanner.nextInt();

        switch (variable) {
            case "año":
                fecha = fecha.plusYears(suma);
            break;
            case "mes":
                fecha = fecha.plusMonths(suma);
            break;
            case "dia":
                fecha = fecha.plusDays(suma);
            break;
        }

        System.out.println(fecha);


    }
}


        System.out.println("Indique la fecha con barras");
        String fecha1 = scanner.next();
        String[] partes = fecha1.split("/");
        String diaString = partes[0];
        String mesString = partes[1];
        String añoString = partes[2];
        int dia = Integer.parseInt(diaString);
        int mes = Integer.parseInt(mesString);
        int año = Integer.parseInt(añoString);


import java.text.SimpleDateFormat;
import java.time.*;
import java.time.format.DateTimeFormatter;
import java.time.temporal.TemporalAdjusters;
import java.util.Date;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Indique el formato de la fecha:");
        System.out.println("dd/MM/yyyy");
        System.out.println("yyyy-MM-dd");
        System.out.println("dd-MM-yyyy");
        String formato = scanner.next();

        System.out.println("Introduce una fecha");
        String fechaString = scanner.next();

        DateTimeFormatter formato1 = null;

        switch (formato) {
            case "dd/MM/yyyy":
                formato1 = DateTimeFormatter.ofPattern("dd/MM/yyyy");
                break;
            case "yyyy-MM-dd":
                formato1 = DateTimeFormatter.ofPattern("yyyy-MM-dd");
                break;
            case "dd-MM-yyyy":
                formato1 = DateTimeFormatter.ofPattern("dd-MM-yyyy");
                break;
        }

        try {
            System.out.println(formato1.format(LocalDate.parse(fechaString,formato1)));
        } catch (final DateTimeException exception) {
            System.out.println("No se ha podido formatear la fecha");
        }
    }
}


import java.time.*;
import java.time.format.DateTimeFormatter;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Indique el formato de la fecha:");
        System.out.println("dd/MM/yyyy");
        System.out.println("yyyy-MM-dd");
        System.out.println("dd-MM-yyyy");
        DateTimeFormatter formato1 = DateTimeFormatter.ofPattern(scanner.next());
        
        System.out.println("Introduce dos fechas");
        String fechaString1 = scanner.next();
        String fechaString2 = scanner.next();
        
        try {
            System.out.println(formato1.format(LocalDate.parse(fechaString1,formato1)));
        } catch (final DateTimeException exception) {
            System.out.println("No se ha podido formatear la fecha");
        }
        try {
            System.out.println(formato1.format(LocalDate.parse(fechaString2,formato1)));
        } catch (final DateTimeException exception) {
            System.out.println("No se ha podido formatear la fecha");
        }

        System.out.println("Cambio de formato");
        System.out.println("dd/MM/yyyy");
        System.out.println("yyyy-MM-dd");
        System.out.println("dd-MM-yyyy");

        DateTimeFormatter formato2 = DateTimeFormatter.ofPattern(scanner.next());
        
        LocalDate dia1 = LocalDate.parse(fechaString1,formato1);
        LocalDate dia2 = LocalDate.parse(fechaString2,formato1);
        System.out.println(dia1.format(formato2));
        System.out.println(dia2.format(formato2));

        Period diferencia = Period.between(dia1,dia2);
        System.out.println(diferencia.getDays()+ " dias " + diferencia.getMonths()+ " meses "  + diferencia.getYears() + " años ");
        
    }
}

// Francisco López Marín
import java.time.*;
import java.time.format.DateTimeFormatter;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Indique el formato de la fecha:");
        System.out.println("dd/MM/yyyy");
        System.out.println("yyyy-MM-dd");
        System.out.println("dd-MM-yyyy");
        DateTimeFormatter formato1 = DateTimeFormatter.ofPattern(scanner.next());

        System.out.println("Introduce una fecha");
        String fechaString1 = scanner.next();
        LocalDate dia1 = null;


        try {
            dia1 = LocalDate.parse(fechaString1,formato1);
        } catch (final DateTimeException exception) {
            System.out.println("No se ha podido formatear la fecha");
        }

        LocalDate hoy = LocalDate.now();


        Period diferencia = Period.between(dia1,hoy);
        if (diferencia.getYears() >= 18) {
            System.out.println("Es mayor de edad");
        } else {
            System.out.println("NO Es mayor de edad");
        }
    }
}


import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Introduce una palabra");
        String cadena = scanner.next();
        if (estaOrdenadoAlfabeticamente(cadena)) {
            System.out.println("La cadena está ordenada alfabéticamente.");
        } else {
            System.out.println("La cadena no está ordenada alfabéticamente.");
        }
    }

    public static boolean estaOrdenadoAlfabeticamente(String str) {
        // Llamada al método recursivo
        return estaOrdenadoAlfabeticamente(str, 0);
    }

    private static boolean estaOrdenadoAlfabeticamente(String str, int indice) {
        // Si el índice es igual a la longitud de la cadena - 1, significa que hemos
        // llegado al final de la cadena y está ordenada.
        if (indice == str.length() - 1) {
            return true;
        } else {
            // Compara el carácter actual con el siguiente y llama recursivamente al método
            // con el siguiente índice.
            return str.charAt(indice) <= str.charAt(indice + 1) && estaOrdenadoAlfabeticamente(str, indice + 1);
        }
    }
}

public class Main {
    public static void main(String[] args) {

        int[] numeros = new int[10];

        for (int j = 0; j<numeros.length;j++) {
            numeros[j] = j + 1;
        }

        for (int i = 0; i<numeros.length;i++) {
            System.out.println(numeros[i]);
        }
    }
}
