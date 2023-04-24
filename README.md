# ejercicios
public static int sumarTresNumeros(int num1, int num2, int num3) {
    int resultado = num1 + num2 + num3;
    return resultado;
   }
   public static void main(String[] args) {
    int resultado = sumarTresNumeros(5, 10, 15);
    System.out.println(resultado);
}
ublic class Coche {
    private int numPuertas;
    
    public Coche(int numPuertas) {
        this.numPuertas = numPuertas;
    }
    
    public void incrementarPuertas() {
        this.numPuertas++;
    }
    
    public int getNumPuertas() {
        return this.numPuertas;
    }
}public static void main(String[] args) {
    Coche miCoche = new Coche(3); // Crear objeto Coche con 3 puertas
    miCoche.incrementarPuertas(); // Incrementar puertas en 1
    System.out.println("Mi coche tiene " + miCoche.getNumPuertas() + " puertas."); // Mostrar número de puertas
}
