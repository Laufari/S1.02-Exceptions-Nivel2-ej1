# S1.02-Exceptions-Nivel2-ej1
 Proyecto Entrada - Manejo de excepciones al leer datos por teclado
 
📄 Descripción - Enunciado del ejercicio
Este proyecto consiste en crear una clase llamada Entrada,
cuya función es manejar las excepciones más comunes que pueden ocurrir al leer datos desde el teclado usando la clase Scanner en Java.
Los métodos de la clase permiten leer varios tipos de datos como byte, int, float, double, char, String y boolean, 
asegurando que la entrada del usuario sea válida.

Cuando se detecta una entrada incorrecta (como un tipo de dato que no coincide con el esperado),
el programa captura la excepción correspondiente y solicita al usuario que ingrese los datos nuevamente hasta que se introduzca correctamente.

💻 Tecnologías Utilizadas
Java 8 o superior

IDE: IntelliJ IDEA Community Edition o cualquier otro IDE que soporte Java

Librerías: Scanner (Java Standard Library)

📋 Requisitos
JDK versión 8 o superior

IDE como IntelliJ IDEA o Eclipse para desarrollar el proyecto

Conexión a Internet para descargar las dependencias (si fuera necesario)

🛠️ Instalación
Clona este repositorio en tu máquina local:
git clone https://github.com/Laufari/Exceptions-Nivel2-Ej1.git
Accede al directorio del proyecto:
cd Exceptions-Nivel2-Ej1
Si utilizas un IDE como IntelliJ IDEA, abre el proyecto y asegúrate de que el JDK esté configurado correctamente.

No se requieren dependencias adicionales fuera de las estándar de Java.

▶️ Ejecución
Para ejecutar el proyecto, abre el archivo Entrada.java en tu IDE.

Ejecuta el programa, que pedirá al usuario ingresar varios tipos de datos (como byte, int, float, etc.). 
Si se introduce un dato incorrecto, el programa mostrará un mensaje de error y seguirá pidiendo la entrada.

Puedes probar cada uno de los métodos de la clase Entrada, que capturan excepciones como InputMismatchException y otras personalizadas.

🌐 Despliegue
Este proyecto está diseñado para ejecutarse de manera local y no requiere un entorno de servidor o de producción específico.
Simplemente ejecuta el archivo Java en tu entorno local para probar la funcionalidad.

🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar el proyecto o agregar nuevas funcionalidades, sigue estos pasos:

Haz un fork del repositorio.

Crea una nueva rama:
git checkout -b feature/NuevaFuncionalidad
Realiza tus cambios y haz un commit:
git commit -m "Añadir nueva funcionalidad"
Sube los cambios a tu rama:
git push origin feature/NuevaFuncionalidad
Haz un pull request explicando los cambios realizados
