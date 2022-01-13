# core-code-myTask

# Challenges of the week (Tuesday)💻--------------------------------------------------------

### Challenge 1: video compilation and interpretation.
  **Answer: Task Completed.**
  *Compilation: Is a translation process through a program called a compiler, which creates a separate file that does not need any other program to run it. 
Interpretation: Program that executes the source code that has just been translated into an intermediate form, or can refer to the program that performs both the translation and the execution.*
            
### Challenge 2: Is Java a language that is compiled or interpreted?.
   **Answer: Task Completed.**
   *Java is a compiled language, since it uses a two-step compilation process. The code is executed by a Java virtual machine (JVM), which uses a technique called Just-in-Time compilation (JIT) to compile the code into native instructions understood by the CPU.*
           
### Challenge 3: Create an algorithm to calculate the equivalent of your local currency to USD
   **Answer: Task Completed.**
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

### Challenge 4: Read about Pseudocode.
   **Answer: Task Completed.**
   *Pseudocode is fake code, which allows us to informally write programs that represent the sequence of actions and instructions and say algorithms that are easy to understand.*
           
### Challenge 5: Why is pseudocode useful?
   **Answer: Task Completed.**
   *The pseudocode is useful because it allows us to simply enter the programming, since it allows us to plan instructions that follow a logical pattern, without including all the technical details.*

### Challenge 6: Create a pseudocode to calculate the approximate age of a user base in the year they were born. 
   **Answer: Task Completed.**
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
          
### Challenge 7: Read about flow diagrams.
  **Answer: Task Completed.**
  *A flowchart is a diagram that describes a process or computer algorithm. They are widely used in many fields to plan and communicate processes that are often complex in diagrams that are easy to understand.*

### Challenge 8: Why are flowcharts important to us as developers?
  **Answer: Task Completed.**
   *Flow diagrams for us as developers are important because they allow us to schematic certain logical processes of creating a program.*
   
### Challenge 9: Search for high-level languages and low-level languages.
  **Answer: Task Completed.**
  *High-Level: They are those that are closer to natural language than machine language. They are aimed at solving problems by using Dynamic Data Structures.
  Low-Level: They are totally machine-dependent languages, meaning that the program that is performed with this type of language cannot be migrated or used in other machines.*


# Challenges of the week (Wednesday) 💻--------------------------------------------------------

### More information on binary, decimal and hexadecimal numbers
  **Answer: Task Completed.**
  *The binary numbers are in "base 2" and start counting from 0, and then 1, but increase by 1 the number on the left. For example: 000, 001, 010...*
  *Decimal numbers are used to represent numbers smaller than the unit, and are written to the right of the Units separated by a comma. For example: Hundreds Tens Units , Tenths Thousandths*
  *Hexadecimal numbers use the 16-digit base. These are like decimals up to 9, but then the letters ("A', "B", "C", "D", "E", "F") are included for values from 10 to 15. So with a single figure, this system can give 16 different values instead of the 10 common ones. For example: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F*
  
### Translate the year you were born to binary, decimal, and hexadecimal
  **Answer: Task Completed.**
  ``
..................................
|Division | Quotient |  Binary   |
|by 16    | integer  | remainder |
|---------|----------|-----------|
| 1999/2  |   999    |     1     |
| 999/2   |   499    |     1     |
| 499/2   |   249    |     1     |
| 249/2   |   124    |     1     |
| 124/2   |   62     |     0     |
| 62/2    |   31     |     0     |
| 31/2    |   15     |     1     |
| 15/2    |   7      |     1     |
| 7/2     |   3      |     1     |
| 3/2     |   1      |     1     |
| 1/2     |   0      |     1     |
|---------|----------|-----------|
[The value in binary is: 11111001111]

..................................................
|Division | Quotient |           |               |
|by 16    | integer  |  Decimal  |  Hexadecimal  |
|---------|----------|-----------|---------------|
| 1999/16 |   124    |    15     |     F         |
| 124/16  |   7	     |    12     |     C         |
| 7/16	   |   0	     |    7      |     7         |
|---------|----------|-----------|---------------|
[The value in hexadec is: 7CF]
  ``
