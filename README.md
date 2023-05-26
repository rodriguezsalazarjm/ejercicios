public class Main {
    public static void main(String[] args) {
        // Condición con if
        int numeroIf = 5;
        if (numeroIf > 0) {
            System.out.println("El número es positivo");
        } else if (numeroIf < 0) {
            System.out.println("El número es negativo");
        } else {
            System.out.println("El número es 0");
        }

        // Bucle While
        int numeroWhile = 0;
        while (numeroWhile < 3) {
            numeroWhile++;
            System.out.println("Valor del número (While): " + numeroWhile);
        }

        // Bucle Do-While
        int numeroDoWhile = 0;
        do {
            numeroDoWhile++;
            System.out.println("Valor del número (Do-While): " + numeroDoWhile);
        } while (numeroDoWhile < 3);

        // Bucle For
        for (int numeroFor = 0; numeroFor <= 3; numeroFor++) {
            System.out.println("Valor del número (For): " + numeroFor);
        }

        // Switch
        String estacion = "verano";
        switch (estacion) {
            case "primavera":
                System.out.println("Estamos en primavera");
                break;
            case "verano":
                System.out.println("Estamos en verano");
                break;
            case "otoño":
                System.out.println("Estamos en otoño");
                break;
            case "invierno":
                System.out.println("Estamos en invierno");
                break;
            default:
                System.out.println("El valor de la variable no corresponde a una estación");
                break;
        }
    }
}

