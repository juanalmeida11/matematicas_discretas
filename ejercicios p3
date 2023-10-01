import javax.swing.*;
import java.util.Scanner;

public class Entrega_p3 {
    public static void main(String[] args) {
        int opcion;
        Scanner scanner = new Scanner(System.in);

        int confirmacion;
        do {
            opcion=Integer.parseInt(JOptionPane.showInputDialog(null,"Opciones: \n" +
                    "1. Comprobar si un numero es divisible por 3 y 5\n" +
                    "2. Verificar usuario y contrasena\n" +
                    "3. Comprobar si un numero es par o multiplo de 3\n" +
                    "4. Comprobar acceso de administrador\n" +
                    "5. Validar un numero entero no negativo\n" +
                    "6. Verificar calificacion de estudiante\n" +
                    "7. Solicitar tarjeta de credito\n" +
                    "8. Abrir puerta con llave\n" +
                    "9. Comprobar si un numero es par\n" +
                    "10. Verificar usuario y codigo de verificacion\n" +
                    "11. Comprobar acceso a red\n" +
                    "12. Intercalar palabras y numeros\nSu seleccion:"));



            if (opcion > 0 && opcion <= 12) {
                System.out.println("--------------------------- Ejercicio " + opcion + " -------------------------------");
                switch (opcion) {
                    case 1:
                        int numero;
                        numero = Integer.parseInt(JOptionPane.showInputDialog("ingrese un numero"));
                        if (numero % 3 == 0 && numero % 5 == 0) {
                            JOptionPane.showMessageDialog(null, "el numero es divisible por 3 y por 5");
                        } else {
                            JOptionPane.showMessageDialog(null, "no es divisible por 3 y por 5");

                        }
                        break;

                    case 2:
                        String id, id1, contraseña, contraseña1;
                        id = "usuario123";
                        contraseña = "contraseña456";
                        id1 = JOptionPane.showInputDialog("ingrese el usuario de ingreso");
                        contraseña1 = JOptionPane.showInputDialog("ingrase la Contraseña");

                        if (id.equals(id1) && contraseña.equals(contraseña1)) {
                            JOptionPane.showMessageDialog(null, "puede ingresar");
                        } else {
                            JOptionPane.showMessageDialog(null, "no puede ingresar");

                        }
                        break;
                    case 3:
                        int numero3;
                        numero3 = Integer.parseInt(JOptionPane.showInputDialog("ingrese un numero para ser evaluado"));
                        if (numero3 % 2 == 0) {
                            JOptionPane.showMessageDialog(null, "el numero es divisible por 3 o es numero par");
                        } else if (numero3 % 3 == 0) {
                            JOptionPane.showMessageDialog(null, "el numero es divisible por 3 o es numero par");
                        } else {
                            JOptionPane.showMessageDialog(null, "el numero ingresado no es divisible por 3 y no es par ");

                        }
                        break;

                    case 4:
                        int experiencia;
                        String admin;
                        admin = JOptionPane.showInputDialog("¿eres administrador? si/no ");
                        experiencia = Integer.parseInt(JOptionPane.showInputDialog("ingrese su experiencia"));
                        if (admin.equals("si") || experiencia >= 1000) {
                            JOptionPane.showMessageDialog(null, "puede ingresar");
                        } else {
                            JOptionPane.showMessageDialog(null, "no puede ingresar");

                        }
                        break;

                    case 5:
                        int numero5;
                        numero5 = Integer.parseInt(JOptionPane.showInputDialog("ingrese un numero"));
                        if (numero5 >= 0) {
                            JOptionPane.showMessageDialog(null, "el numero es valido");
                        } else {
                            JOptionPane.showMessageDialog(null, "el numero es invalido");
                        }
                        break;

                    case 6:
                        int nota;
                        nota = Integer.parseInt(JOptionPane.showInputDialog("ingrese la nota del examen para dar un resultado"));
                        if (nota >= 60) {
                            JOptionPane.showMessageDialog(null, "Estudiante aprobado");
                        } else {
                            JOptionPane.showMessageDialog(null, "estudiante no aprobado");
                        }
                        break;

                    case 7:
                        int ingreso;
                        String credito;
                        ingreso = Integer.parseInt(JOptionPane.showInputDialog("cuales son sus ingresos mensuales"));
                        credito = JOptionPane.showInputDialog("¿tiene credito(s) por pagar?  si/no");
                        if (ingreso >= 2000 && credito.equals("no")) {
                            JOptionPane.showMessageDialog(null, "Puede solicitar una tarjeta de credito");
                        } else {
                            JOptionPane.showMessageDialog(null, "No puede solicitar una tarjeta de credito");

                        }
                        break;

                    case 8:
                        String llave;
                        llave = JOptionPane.showInputDialog("tiene la llave si/no");
                        if (llave.equals("si")) {
                            JOptionPane.showMessageDialog(null, "puede abrir la puerta");
                        } else {
                            JOptionPane.showMessageDialog(null, "No puede abrir la puerta");
                        }
                        break;

                    case 9:
                        int num;
                        num = Integer.parseInt(JOptionPane.showInputDialog("ingrese un numero"));
                        if (num % 2 == 0) {
                            JOptionPane.showMessageDialog(null, "es par");
                        } else {
                            JOptionPane.showMessageDialog(null, "no es par");
                        }
                        break;

                    case 10:
                        String usuario = "usuario12", usuario2, codigo = "159753", codigo2;
                        usuario2 = JOptionPane.showInputDialog("ingrese el nombre de usuario");
                        codigo2 = JOptionPane.showInputDialog("ingrese el codigo de verificacion llegado a su correo electronico");
                        if (usuario2.equals(usuario) && codigo2.equals(codigo)) {
                            JOptionPane.showInputDialog("Acceso concedido");
                        } else {
                            JOptionPane.showMessageDialog(null, "acceso denegado");

                        }
                        break;

                    case 11:
                        String CredencialesAdministrador, ipPermitida;
                        CredencialesAdministrador = JOptionPane.showInputDialog("tiene credenciales de administrador? si/no");
                        ipPermitida = JOptionPane.showInputDialog("¿Su ip se encuentra en la lista de direcciones permitidas? si/no");
                        if (CredencialesAdministrador.equals("si") && ipPermitida.equals("si")) {
                            JOptionPane.showMessageDialog(null, "Acceso concedido");
                        } else {
                            JOptionPane.showMessageDialog(null, "Acceso denegado");
                        }
                        break;

                    case 12:
                        String contrasena;
                        usuario:JOptionPane.showMessageDialog(null,"Ingrese una palabra:");
                        usuario = scanner.next();
                        JOptionPane.showMessageDialog(null, "Ingrese una secuencia numerica:");
                        contrasena = scanner.next();

                        int longitudPalabra = usuario.length();
                        int longitudNumero = contrasena.length();
                        int longitudCifrado = Math.max(longitudPalabra, longitudNumero);

                        StringBuilder resultado = new StringBuilder();

                        for (int i = 0; i < longitudCifrado; i++) {
                            if (i < longitudPalabra) {
                                resultado.append(usuario.charAt(i));
                            }
                            if (i < longitudNumero) {
                                resultado.append(contrasena.charAt(i));
                            }
                        }
                        JOptionPane.showMessageDialog(null, "Palabras intercaladas: " + resultado.toString());
                        break;
                }
            } else {
                JOptionPane.showMessageDialog(null,"Ingrese un numero valido");
            }

            JOptionPane.showMessageDialog(null,"Otro ejercicio:1, Finish:0:");
            confirmacion = scanner.nextInt();

        } while (confirmacion == 1);

        scanner.close();
    }
}

