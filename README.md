# Fundamentos de Java para Principiantes

## Resumen del curso

Este curso introduce a estudiantes de secundaria en la programación con **Java**, desde ejecutar un primer programa hasta organizar información mediante clases y objetos. A lo largo de **diez lecciones**, cada estudiante trabajará en un compilador Java en línea, probará cambios en los ejemplos y reconocerá los resultados en la consola. El proyecto de cierre consiste en un **registro de estudiantes** que permite seleccionar una ficha, actualizar una nota válida y calcular el promedio del grupo.

- **Duración total real de los videos:** **59 minutos y 47 segundos (59:47)**.
- **Público objetivo:** estudiantes de secundaria de 12 a 17 años que se inician en programación.
- **Prerrequisitos:** no se requieren conocimientos previos de programación.
- **Herramientas necesarias:** navegador web y compilador/editor Java en línea. Las lecciones 7 y 10 usan la entrada estándar del programa.

- **Repositorio del código fuente:** PEGAR ENLACE DEL REPOSITORIO

## Secuencia de las lecciones

### Lección 1. Qué es Java y cómo ejecutar un programa (5:45 min)

- **Descripción:** Presenta Java como lenguaje de programación y muestra cómo pasar del código fuente a la ejecución. A través de la clase `Main` y el método `main`, el estudiante imprime un saludo en la consola, realiza una suma y observa la diferencia entre mostrar texto y calcular una expresión.
- **Video (GodEthan):** https://youtu.be/MYSRUFklN5w
- **Conceptos clave:** Algoritmo, código fuente, compilador, `Main`, `main`, `System.out.print`, `System.out.println`, comillas y punto y coma.
- **Actividad práctica:** Cambiar «Hola, clase» por «Hola, Java», comparar `println("3 + 4")` con `println(3 + 4)` y comprobar cómo varía la salida.
- **Ejercicio en el editor:** https://onlinegdb.com/yUr7AppXh

### Lección 2. Declarar variables y elegir tipos (5:28 min)

- **Descripción:** Explica cómo guardar y actualizar información con variables de distinto tipo. El programa registra un alias, puntos, tiempo y estado de una actividad, y permite comprobar cómo el orden de las asignaciones modifica los mensajes en consola.
- **Video (GodEthan):** https://youtu.be/C3eB-PBZ7Jc
- **Conceptos clave:** Declaración y asignación; `String`, `int`, `double` y `boolean`; actualización de valores; concatenación y orden de ejecución.
- **Actividad práctica:** Iniciar `puntos` en 9, sumar 2 y verificar que el mensaje inicial muestre 9 y el final 11.
- **Ejercicio en el editor:** https://onlinegdb.com/T19Y6Tnr6B

### Lección 3. Operadores y expresiones (6:05 min)

- **Descripción:** Enseña a combinar valores para efectuar operaciones y calcular promedios. Con las notas 14 y 17 se compara la división entera con la decimal, se utiliza el residuo y se estudia cómo los paréntesis cambian el orden de las operaciones.
- **Video (GodEthan):** https://youtu.be/qds0meBDY20
- **Conceptos clave:** Suma, multiplicación, división entera y decimal, operador `%`, precedencia, paréntesis y expresiones.
- **Actividad práctica:** Obtener la media 15.5 con `(14 + 17) / 2.0` y contrastarla con el resultado de dividir entre `2`.
- **Ejercicio en el editor:** https://onlinegdb.com/nw2KZx97J

### Lección 4. Decisiones con if, else if y else (6:28 min)

- **Descripción:** Muestra cómo un programa elige una respuesta según una nota. Primero se valida que esté entre 0 y 20 y, después, se determina si alcanza la meta de 11; se contrastan casos normales, valores límite y datos fuera de rango.
- **Video (GodEthan):** https://youtu.be/nzvwXhYHX0Q
- **Conceptos clave:** Condiciones booleanas, comparadores, operador lógico `||`, `if`, `else if`, `else` y validación de rangos.
- **Actividad práctica:** Probar las notas 10, 11 y 21; luego cambiar la meta a 12 y verificar qué ocurre con 11 y 12.
- **Ejercicio en el editor:** https://onlinegdb.com/Fplc7uADA

### Lección 5. Repeticiones con for y while (6:08 min)

- **Descripción:** Introduce dos maneras de repetir instrucciones. Un bucle `for` suma los valores del 1 al 4 hasta llegar a 10 y un `while` realiza una cuenta atrás desde 3; se examina la importancia de los contadores, acumuladores y condiciones de salida.
- **Video (GodEthan):** https://youtu.be/Tv2xfjbQdCo
- **Conceptos clave:** `for`, `while`, contador, acumulador, incremento, condición y terminación de bucles.
- **Actividad práctica:** Ajustar el límite del `for` para sumar únicamente 1, 2 y 3, y comprobar que el acumulado final sea 6.
- **Ejercicio en el editor:** https://onlinegdb.com/v7WQEBqxs

### Lección 6. Métodos y parámetros (6:27 min)

- **Descripción:** Explica cómo dividir un programa en métodos que reciben argumentos y pueden devolver resultados. Se define un método para calcular promedios, otro para mostrarlos y uno más para comprobar si se alcanza una meta.
- **Video (GodEthan):** https://youtu.be/zXs4STtasZA
- **Conceptos clave:** Métodos, parámetros, argumentos, `return`, `void`, tipos de retorno y llamadas entre métodos.
- **Actividad práctica:** Ejecutar `mostrar("Luz", promedio(18, 12))` y comprobar el mensaje «Luz | promedio 15.0».
- **Ejercicio en el editor:** https://onlinegdb.com/fXGxuLK9U

### Lección 7. Entrada y salida con Scanner (6:30 min)

- **Descripción:** Permite que la persona ingrese un alias completo y una nota desde la entrada estándar del editor. El ejemplo lee el texto con `nextLine`, comprueba que la nota sea un entero y valida tanto el alias como el intervalo de 0 a 20.
- **Video (GodEthan):** https://youtu.be/BSyRjtfnE84
- **Conceptos clave:** `Scanner`, `System.in`, `nextLine`, `trim`, `hasNextInt`, `nextInt`, validación y `return`.
- **Actividad práctica:** Ingresar «Sol Azul» y 16 en dos líneas, después probar una nota no numérica, otra fuera de rango y un alias vacío.
- **Ejercicio en el editor:** https://onlinegdb.com/V_xV4pinw

### Lección 8. Clases, objetos y constructores (6:50 min)

- **Descripción:** Introduce la programación orientada a objetos mediante la clase `Estudiante`, que reúne alias, nota y un método para mostrar la ficha. Se crean dos objetos independientes con `new`, se inicializan con un constructor y se modifica la nota de uno sin alterar la del otro.
- **Video (GodEthan):** https://youtu.be/C_qsN1tH0Ag
- **Conceptos clave:** Clase, objeto, atributo, instancia, `new`, constructor, `this` y método de instancia.
- **Actividad práctica:** Crear una tercera ficha para «Luz» con nota 12 y ejecutar `mostrarFicha()` para comprobar sus datos.
- **Ejercicio en el editor:** https://onlinegdb.com/H5zret1yy

### Lección 9. Encapsulación con getters y setters (5:03 min)

- **Descripción:** Presenta la encapsulación para impedir cambios arbitrarios en la nota de un estudiante. Los atributos se declaran privados; los getters permiten consultarlos y `setNota` acepta solo notas entre 0 y 20, conservando el último valor válido ante una solicitud incorrecta.
- **Video (GodEthan):** https://youtu.be/Bb6TG8CfyPY
- **Conceptos clave:** `private`, encapsulación, `getAlias`, `getNota`, `setNota`, validación y resultado booleano.
- **Actividad práctica:** Actualizar una ficha a 18 e intentar después asignarle 25; comprobar que el setter devuelve `false` y la nota permanece en 18.
- **Ejercicio en el editor:** https://onlinegdb.com/tpZSCOR53

### Lección 10. Proyecto final: registro de estudiantes (5:03 min)

- **Descripción:** Integra lo aprendido en un registro de estudiantes por consola. Un arreglo contiene las fichas de Sol, Mar y Luz; el usuario elige una opción, escribe una nota válida y el programa actualiza la ficha seleccionada y calcula el promedio del grupo.
- **Video (GodEthan):** https://youtu.be/kUVV5sPzC3w
- **Conceptos clave:** Arreglos de objetos, índices, `length`, recorridos `for`, `Scanner`, validaciones, setters y promedio decimal.
- **Actividad práctica:** Introducir la opción 2 y la nota 19: la ficha de Mar debe actualizarse y el promedio del grupo debe ser 15.0. Como ampliación, agregar un cuarto estudiante.
- **Ejercicio en el editor:** https://onlinegdb.com/l3fMPGGTI

## Recursos adicionales

**Código fuente completo:** PEGAR ENLACE DEL REPOSITORIO

**Todas las actividades prácticas**

| Lección | Actividad | Enlace para practicar |
|---|---|---|
| 1 | Ejecutar el primer programa y comparar texto con operaciones | https://onlinegdb.com/yUr7AppXh |
| 2 | Declarar variables y actualizar una puntuación | https://onlinegdb.com/T19Y6Tnr6B |
| 3 | Calcular promedios y distinguir división entera | https://onlinegdb.com/nw2KZx97J |
| 4 | Validar notas y elegir mensajes condicionales | https://onlinegdb.com/Fplc7uADA |
| 5 | Recorrer bucles y seguir un acumulador | https://onlinegdb.com/v7WQEBqxs |
| 6 | Crear métodos para calcular y mostrar promedios | https://onlinegdb.com/fXGxuLK9U |
| 7 | Leer un alias y validar la nota recibida | https://onlinegdb.com/V_xV4pinw |
| 8 | Crear objetos Estudiante independientes | https://onlinegdb.com/H5zret1yy |
| 9 | Proteger las notas con getters y setters | https://onlinegdb.com/tpZSCOR53 |
| 10 | Seleccionar una ficha, modificar su nota y calcular el promedio | https://onlinegdb.com/l3fMPGGTI |

**¡Gracias por completar el curso de Java básico!**

## Elaboración

Universidad Peruana de Ciencias Aplicadas  
Carrera de Ingeniería de Software  
Asignatura: Aplicaciones Open Source  
Periodo académico: 2026
NRC: 7760

- **Nombre del equipo:** Proxy
- **Líder del equipo:** Mateo Caldas Bravo
- **Integrantes del equipo:**
  - Dany Yohel Chavez Sandoval
  - Giordano Sebastian Del Ángel Trejo Espejo
  - Jhorch Jhoseff Blanco Medina
  - Johan Alvaro Saravia Hiso
  - Mateo Caldas Bravo
- **Fecha de entrega:** 13/11/2026
