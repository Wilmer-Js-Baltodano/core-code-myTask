# core-code-myTask
 Mis tareas 
 
# Primera semana

### Desafío 1: video sobre compilación e interpretación.
   **Respuesta: Tarea completada.**
   *La compilación: Proceso de traducción a través de un programa llamado compilador, este crea un archivo independiente que no necesita ningún otro programa para ejecutarse a sí mismo. 
   Interpretación: Programa que ejecuta el código fuente que acaba de ser traducido a una forma intermedia, o puede hacer referencia al programa que lleva a cabo tanto la traducción como la ejecución.*
            
### Desafío 2: ¿El lenguaje Java se compila o interpreta?.
   **Respuesta: Tarea completada.**
  *Java sí es un lenguaje compilado, ya que utiliza un proceso de compilación de dos pasos. El código es ejecutado por una máquina virtual Java (JVM), las cuales utilizan una técnica llamada compilación Just-in-Time (JIT) para compilar el código en instrucciones nativas entendidas por la CPU.*
           
###  Desafío 3: Cree un algoritmo para calcular el equivalente de su moneda local a USD.
   **Respuesta: Tarea completada.**
   ``
   Algoritmo cambio_divisa

   // "moneda_local (a)", dinero que se estará en la moneda.
   // "equivalente (b)", tasa de conversión (modena extranjera), 
   // "result_mult (c)", resultado del dinero que se obtendrá tras el cambio. 

   // Formululas:
   // a * b = c (c = a * b)
   // a = c/b, da como resutado la forma invertida de la conversión

   // Declaración de variable tipo boleanas
   Definir moneda_local, equivalente, resultado como real;

   moneda_local = 0.00000;
   equivalente = 0.00157;

   Escribir "Escriba la cantidad en colones a convertir:" ;
   leer moneda_local; //captura el valor por teclado 

   resultado <- moneda_local * equivalente; //cálculo que permite la conversión a dolar USD
   Escribir "El resultado es: ", resultado, " USD";

   FinAlgoritmo
   ``

### Desafío 4: Leer sobre Pseudocode.
   **Respuesta: Tarea completada.**
   *El pseudocódigo es codigo falso, que nos permite de una forma informal escribir programas en los que se representa la secuencia de acciones e instrucciones e decir algoritmos que son simples de entender*.
           
#### Desafío 5: ¿Por qué es útil el pseudocódigo?
   **Respuesta: Tarea completada.**
   *El pseudocódigo es util porque nos permite de forma simple adentrarnos a la programación, ya que permite planificar instrucciones que siguen un patrón lógico, sin incluir todos los detalles técnicos*.

### Desafío 6: Cree un pseudocódigo para calcular la edad aproximada de una base de usuarios en el año en que nacieron. 
   **Respuesta: Tarea completada.**
   ``
   Algoritmo calculo_edades

   // Descripción: Cree un pseudocódigo para calcular la edad aproximada de una base de usuarios en el año en que nacieron 

   // Declaración de variables
   definir anioActual, anioNacim, edadPersona como entero;

   anioActual <- 2022;

   // Se espera a que el usuario ingrese un valor y presiones enter.
   Escribir "Ingrese su año de nacimiento: ";
   leer anioNacim;

   // Se realiza el proceso de cálculo.
   edadPersona <- anioActual - anioNacim;

   // Se iprimir por pantalla la edad actual de la persona.
   Escribir "Su edad es: ", edadPersona, " años";
   FinAlgoritmo
   ``
          
### Desafío 7: Lea sobre diagramas de flujo.
   **Respuesta**: en proceso.

### Desafío 8: ¿Por qué los diagramas de flujo son importantes para nosotros como desarrolladores?.
   **Respuesta**: en proceso.

### Desafío 9: Busque sobre idiomas de alto nivel e idiomas de bajo nivel.
   **Respuesta**: en proceso.
