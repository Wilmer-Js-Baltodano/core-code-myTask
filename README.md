# core-code-myTask

# Challenges of the week (Tuesday)💻----------

### Challenge 1: video compilation and interpretation.
  **Answer: Task Completed.**
  *Compilation: Is a translation process through a program called a compiler, which creates a separate file that does not need any other program to run it. 
Interpretation: Program that executes the source code that has just been translated into an intermediate form, or can refer to the program that performs both the translation and the execution.*
            
### Challenge 2: Is Java a language that is compiled or interpreted?.
   **Answer: Task Completed.**
   *Java is a compiled language, since it uses a two-step compilation process. The code is executed by a Java virtual machine (JVM), which uses a technique called Just-in-Time compilation (JIT) to compile the code into native instructions understood by the CPU.*
           
### Challenge 3: Create an algorithm to calculate the equivalent of your local currency to USD
   **Answer: Task Completed.**
```
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
```

### Challenge 4: Read about Pseudocode.
   **Answer: Task Completed.**
   *Pseudocode is fake code, which allows us to informally write programs that represent the sequence of actions and instructions and say algorithms that are easy to understand.*
           
### Challenge 5: Why is pseudocode useful?
   **Answer: Task Completed.**
   *The pseudocode is useful because it allows us to simply enter the programming, since it allows us to plan instructions that follow a logical pattern, without including all the technical details.*

### Challenge 6: Create a pseudocode to calculate the approximate age of a user base in the year they were born. 
   **Answer: Task Completed.**
```
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
```
          
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


# Challenges of the week (Wednesday) 💻----------

### Challenge 1: More information on binary, decimal and hexadecimal numbers
  **Answer: Task Completed.**
  *The binary numbers are in "base 2" and start counting from 0, and then 1, but increase by 1 the number on the left. For example: 000, 001, 010...*
  *Decimal numbers are used to represent numbers smaller than the unit, and are written to the right of the Units separated by a comma. For example: Hundreds Tens Units , Tenths Thousandths*
  *Hexadecimal numbers use the 16-digit base. These are like decimals up to 9, but then the letters ("A', "B", "C", "D", "E", "F") are included for values from 10 to 15. So with a single figure, this system can give 16 different values instead of the 10 common ones. For example: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F*
  
### Challenge 2: Translate the year you were born to binary, decimal, and hexadecimal
  **Answer: Task Completed.**
  
| Division by 2 | Quotient integer | Binary remainder |
|---------------|------------------|------------------|
| 1999 / 2      |     999          |       1          |
| 999 / 2       |     499          |       1          |
| 499 / 2       |     249          |       1          |
| 249 / 2       |     124          |       1          |
| 124 / 2       |     62           |       0          |
| 62 / 2        |     31           |       0          |
| 31 / 2        |     15           |       1          |
| 15 / 2        |     7            |       1          |
| 7 / 2         |     3            |       1          |
| 3 / 2         |     1            |       1          |
| 1 / 2         |     0            |       1          |

[The value in binary is: 11111001111]


| Division by 16 | Quotient integer | Decimal remainder | Hexadecimal remainder |
|----------------|------------------|-------------------|-----------------------|
| 1999 / 16      |     124          |       15          |       F               |
| 124 / 16       |     7	           |       12          |       C               |
| 7 / 16	        |     0	           |       7           |       7               |

[The value in hexadec is: 7CF]

### Challenge 3: Translate 51966 into hexadecimal and binary.
  **Answer: Task Completed.**

| Division by 2 | Quotient integer | Binary remainder |
|---------------|------------------|------------------|
| 51966 / 2     |=     25983       |       0          |
| 25983 / 2     |=     12991       |       1          |
| 12991 / 2     |=     6495        |       1          |
| 6495  / 2     |=     3247        |       1          |
| 3247  / 2     |=     1623        |       1          |
| 1623 / 2      |=     811         |       1          |
| 811  / 2      |=     405         |       1          |
| 405  / 2      |=     202         |       1          |
| 202  / 2      |=     101         |       0          |
| 101 / 2       |=     50          |       1          |
| 50 / 2        |=     25          |       0          |
| 25 / 2        |=     12          |       1          |
| 12 / 2        |=     6           |       0          |
| 6  / 2        |=     3           |       0          |
| 3  / 2        |=     1           |       1          |
| 1  / 2        |=     0           |       1          |

[The value in hexadec is: 1100101011111110]

| Division by 16 | Quotient integer | Decimal remainder | Hexadecimal remainder |
|----------------|------------------|-------------------|-----------------------|
| 51966 / 16     |     3247         |       14          |          E            |
| 3247 / 16      |     202	    |       15          |          F            |
| 202 / 16	 |     12	    |       10          |          A            |
| 12 / 16	 |     0	    |       12          |          C            |

[The value in hexadec is: CAFE]

### Challenge 4: Use a Low-level language, for example MIPS aseembler.
  **Answer: Task Completed.**
  *Reading the completed guide.*
  *Reading of the completed presentation. *
  
 ### Challenge 5: Based on the examples and guidance on the low-level language:
- 5.1 Create a program to add two numbers given by the user
```
.data
	title: .asciiz "\n CALCULADORA \n" 
	firstNum: .asciiz "\nDigite el primer número: "
	secondNum: .asciiz "\nnDigite el segundo número: "
        result: .asciiz "\nEl resultado es: "
.text 

	main:
	// Mostramos el título del sistema
		li $v0, 4
		la $a0, title
	syscall
	
	// se solicita el primer valor numérico
		li $v0, 4
		la $a0, firstNum
	syscall 
	// capturamos el primer número
	li $v0, 5
	syscall 
	// el comando move: nos permitirá mover el valor a otro registro.
	move $t0, $v0
	
	//--------------------------
	
	//se solicita el segundo valor numérico
		li $v0, 4
		la $a0, secondNum
	syscall 
	
	// capturamos el primer número
		li $v0, 5
	syscall 
	
	// repetimos, movemos el segundo valor a otro registro.
	move $t1, $v0
	
	// Procedemos a realizar el cálculo y almacenamos el resultado en t$2
	add $t2, $t0, $t1
	
		// Mostramos el mensaje "El resultado es:"
		li $v0, 4
		la $a0, result
		syscall 
	
		// mostramos el resultado de la operación
		li $v0, 1
		move $a0, $t2
	syscall
```

- 5.2 Create a program that display your name
```
.data
       name: .asciiz "\n Nombre del usuario: \n Wilmer \n"
       birthday: .asciiz "\nIngrese su año de nacimiento: "
       result: .asciiz "\n su edad es: "
.text
	main:
	li $t2, 2022 
	
	// solicitamos el nombre de usuario
		li $v0, 4
		la $a0, name
	syscall 
		
	//--------------------------
	
	// solicitamos el año de nacimiento del usuario
		li $v0, 4
		la $a0, birthday
	syscall 
	
	// capturamos ese dato ingresado
		li $v0, 5
	syscall 
	
	// movemos el valor a otro registro(t1).
	move $t1, $v0
	
	// Mostramos el mensaje
		li $v0, 4
		la $a0, result
	syscall 
	
	sub $t3, $t2, $t1 // realizamos la resta usando el comando (sub)
	
	// mostramos el resultado de la operación, edad del usuario
		li $v0, 1
		move $a0, $t3
	syscall
```

# Challenges of the week (Thursday) 💻----------

### Challenge 1: Applications that use Javascript.
  **Answer: Task Completed.**
  
  *Canvascape: Game in first person (Doom style) that gives proof of the power of this technology.*
  
  *MSX Emulator: This project shows the true power of javascript (it was an 8-bit microcomputer architecture) that includes the possibility of loading and running the roms.*
  
### Challenge 2: Video about the history of the internet
  **Answer: Task Completed.**
  *History of the Internet: It all started as an idea of a computer network created to allow general communication between users of multiple computers. The infrastructure of this idea spread throughout the world, to create the modern global computer network that we now know as the internet.*
  
### Challenge 3: Video about the triumph of the Nerds
  *Answer: Task Completed.*

### Challenge 4: github course
  *Answer: Task Completed.*
    -Courses
     Git: Git course reviewed and in practice.
    -Videos
     Clean Code: Clean code video completed
    -Articles
     Markdown Cheat Sheet: The page about Markdown Cheat Sheet reviewed.
     React Introduction: The introduction page to React has been completely revised.
