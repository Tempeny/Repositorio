import java.util.Scanner;


public class Main {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        int opcion = 0;
        do{
            System.out.println("\n*****Bienvenido al simulador espacial*****\n\n"+
            "¿Que deseas hacer?\n\n"+
            "1)Registrar Mision\n"+
            "2)Registar Nave\n"+
            "3)Simular un ciclo\n"+
            "4)Mostrar estado general\n"+
            "5)Buscar Mision\n"+
            "6)Ranking de naves\n"+
            "7)Generar Naves y misiones\n"+
            "8)Salir");
            opcion = scanner.nextInt();
            switch (opcion) {
                case 1:
                  Mision.registrarMision(scanner);
                break;
                case 2:
                  NavesEspaciales.registrarNave(scanner);
                break;
                case 3:
                  //  simularCiclo();
                break;
                case 4:
                  NavesEspaciales.mostrarEstado();
                break;
                case 5:
                  Mision.buscarMisiones(scanner);
                break;
                case 6:
                  NavesEspaciales.generarRanking();
                break;
                case 7:
                  Mision.generarMisiones();
                  NavesEspaciales.generarNaves();  
                  System.out.println("\nNaves y Misiones generados correctamente\n");
                break;
                case 8:
                  System.out.println("Adios!");
                break;

                //Crear caso de logs de Misiones y naves --> Mover líneas 56 y 57 como opción 

            }
        }while (opcion!=8);
        scanner.close();
        //Logs para verificar el funcionamiento
        Mision.logMisiones();
        NavesEspaciales.logNaves();
        }
}
