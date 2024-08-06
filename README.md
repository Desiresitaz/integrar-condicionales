// EJERCICIO INTEGRADOR DE CONDICIONALES

public class Main {
    public static void main(String[] args) {

      double sueldo=0;
      int categoria;


      System.out.println("ingrese el tipo de categoria que desea calcurar el sueldo");
      Scanner teclado = new Scanner (System.in);
      categoria = teclado.nextInt();

      if (categoria == 1){
          sueldo = 15890 + (15890*0.10);
      } else {
          if (categoria == 2){
              sueldo = 25630.89;
          } else {
            if (categoria == 3) {
              sueldo = 35560.20 - (35560.20*0.11);
            } else {
              System.out.println("debe ingresar un numero de categoría válido");
                }
            }

      }
    System.out.println ("el total del sueldo para la categoría seleccionada" + categoria + "el igual a " + sueldo);
}
}
