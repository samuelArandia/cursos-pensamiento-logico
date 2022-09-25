# Cursos de pensamiento Lógico 

Este curso consta de un  trilogia 

# Algoritmos y Diagramas de flujo 

## Operación matemática

Una operacion es un proceso con un resultado como objetivo, posee entradas(2 recursos), símbolos que indican que hacer y que decisión tomar.
    
En la programación su importancia radica: optimizacion en algoritmos y los más importante, darnos la capacidad de estructurar nuestras ideas, de forma más eficiente.
   
Tiene su aplicación en situaciones desde eventos del dia a dia hasta el límite de nuestra imaginacion (ingeniería, matematicas abstractas etc.)

Operaciones matematicas basicas: Suma, multiplicación, resta y  división 

## Propiedades de las operaciones 

### Propiedad comutativa 

El orden de los factores no altera el producto. Ejemplo: 

          3 + 4 = 4 + 3 

### Propieda asociativa 

Cuando se suma o multiplican tres o más números, la operación es la misma sin importa el modo en el que los números osn agrupados. Ejemplo: 

          3 + 2 + 5 = 10 
          
          (3+2) + 5 = 
            5   + 5 = 10 
            
           3 + ( 2 + 5) = 10 
           3 +     7    = 10           
           
### Propiedad Distributiva 

La suma de dos números multiplicando por un tercer número es igula a la suma de cada sumando multiplicando por el tercer número. Ejemplo: 

             8 x (4 + 15) = (8 x 4) + (8 x 15) 
              8 x   19    =  32 +  120 
                    152 =  152
                    
### Propiedad de identidad 

En caso de la suma, la suma de cualquier numero y cero da como resultado el mismo numero 

                5 + 0 = 5 
                
En caso de la multiplicación, el prodcuto de culaquier número y uno da como resultado ese mismo número 

            5 * 0 = 5 

### Sistema Binarrio 

El sistema binario es un método de representación numérica que utiliza la combinación de dos dígitos: 1 y 0 para simbolizar datos, programas ejecutables y texto. En el mundo de la informática, cada uno de estos números conforma un bit binario y un conjunto de 8 bits equivale a un byte.

Al adoptar este sistema se puede establecer el valor positivo o negativo, verdadero o falso de una propiedad o enunciado. En este ejemplo tenemos un bombillo encendido, el cual representa el número 1 y un bombillo apagado, donde no hay corriente y, por lo tanto, representa el valor 0.

![imagen](https://user-images.githubusercontent.com/83564327/190916075-ee833ad7-8486-4827-8c6a-7754addbeef4.png)

Cómo convertir de decimal a binario

Existen varias maneras de convertir números decimales a binarios y esta vez te enseñaremos un método más sencillo e intuitivo para realizar este proceso.

A. Supongamos que quieres encontrar el valor binario de 32.

Crea una lista descendente de números decimales que empiece por el número (en este caso 32) y que, progresivamente, al dividirse por 2 llegue al número 1. También lo puedes ver de esta manera, revisa que valores de la fila de derecha a izquierda correspondan al número anterior multiplicado por 2.

                32 - 16 - 8 - 4 - 2 - 1

Para encontrar el valor en binario, añades el valor 1 en el puesto que si va a ocupar dicho número en esta estructura y pones un 0 en donde no se va a ocupar. ¡Muy bien! Ahora sabemos que el resultado es 100000.


                32 - 16 - 8 - 4 - 2 - 1
                1 -- 0 -- 0 - 0 - 0 - 0

B. Ahora, practiquemos con un ejemplo más complejo, el número 2021.

Simplemente, sumamos los números que necesitamos de la fila preestablecida para obtener el resultado 2021. Añadimos un 1 en los valores que utilizamos y en los que no un 0.

Siendo así, encontramos que 2021 en binario sería: 11111100101.

                1024 - 512 - 256 - 128 - 64 - 32 - 16 - 8 - 4 - 2 - 1
                - 1 --- 1 --- 1 --- 1 -- 1 -- 1 -- 0  - 0 - 1 - 0 - 1
                
![imagen](https://user-images.githubusercontent.com/83564327/191408449-889922a4-2c14-4883-a46b-e604eee974c4.png)
                
Operaciones binarias

Con este sistema de numeración podemos hacer también operaciones aritméticas tal como lo haríamos con el sistema decimal.
Suma binaria

Para sumar debes tener en cuenta 4 arreglos posibles: 0 + 0 = 0; 0 + 1 = 1; 1 + 0 = 1; 1 + 1 = 10. Por lo tanto, el resultado de sumar 1 0 0 1 1 0 0 0 y 0 0 0 1 0 1 0 1 es 1 0 1 0 1 1 0 1.
Resta binaria

Para llevar a cabo una resta también hay 4 combinaciones posibles: 0 - 0 = 0; 1 - 0 = 1; 1 - 1 = 0; 10 - 1 = 1. Si restas los mismos números que usamos para la suma quedaría de la siguiente forma: 1 0 0 1 1 0 0 0 - 0 0 0 1 0 1 0 1 = 1 0 0 0 0 0 1 1
Acarreo

Probablemente, ya te diste cuenta de que existen dos casos especiales en los que utilizamos más de un dígito: 1 + 1 = 1 0 y 1 0 - 1 = 1. Esto se debe al acarreo y es algo que ya conoces del sistema decimal, la diferencia es que en el sistema binario también se puede acarrear de manera negativa.

La resta de 0 - 1 no es posible, es por esto que el 0 pide la ayuda de su compañero de la izquierda y le quita un 1 que le permite realizar la operación. Entonces, el 0 que pidió prestado se convierte en 1 0 y al restarle 1 nos da como resultado 1 0 - 1 = 1.

El compañero que tenía a su izquierda y le cedió el uno, por ende, va a perder ese uno y termina siendo un 0. Si el compañero de la izquierda es un 0, hará el mismo proceso de pedir valores a la izquierda hasta que un 1 pueda prestarles su valor.

Otra manera de verlo es que el resultado de la operación sería así: 1 0 - 1 = 1 1. El resultado tiene dos 1 porque uno de ellos va a ser restado del dígito que está a la izquierda y prestó ese 1.
Multiplicación y división binaria

Funcionan bajo las mismas condiciones que en el sistema decimal, todo número multiplicado por 0 es igual a 0 y solo es 1 cuando se multiplica por 1.

### Conversión entre un binario y un decimal 

28 en decimal es 11100 

![imagen](https://user-images.githubusercontent.com/83564327/191409028-88e5f0b2-4973-4224-8fd4-379fc50e83c7.png)

conversión decimal con python 

![imagen](https://user-images.githubusercontent.com/83564327/191408928-27748874-69a0-4eb8-b78b-e928d8254501.png)

### Suma y resta de binarios 

La mitad de las restas me daban bien y la mitad me daba un número inclusive mayor que los números que estaban restando. Por si hay alguien más con este problema: mi error era que cuando se acarreaba un 1 por encima de un 0 estaba restando 1 - 0 cuando el orden correcto es 0 - 1.
Volví a revisar el video y la profesora señala el orden de esa resta de forma equivocada, primero señala el 1 acarreado y luego le resta el número de abajo (lo que en el ejemplo que ella da no cambia nada porque es 1 - 1).

Suma
        La suma de 0 + 0 es 0
        La suma de 1 + 0 es 1
        La suma de 0 + 1 es 1
        La suma de 1 + 1 es 10, llevando 1 al numero a la izquierda inmediata.
        
Resta
    
        La resta de 0 - 0 es 0
        La resta de 1 - 1 es 0
        La resta de 1 - 0 es 1
        La resta de (1)0 - 1 es 1

### Multiplicacón y la división 

Multiplicación: Todo número multiplicado por 0 es igual a 0

0 x 0 = 0
0 x 1 = 0
1 x 0 = 0
1 x 1 = 1

Ejemplo

        1 1 0 · 1 0 = 1 1 0 0
        
Realizamos el procedimiento como en una multiplicación normal (sumando el resultado de los productos)

División 

Tener en cuenta cuál es el· Dividendo· y el · Divisor ·

¿El divisor es menor al número que estoy tomando?
Si no ❌ = 0 y no se puede restar
Si es igual (﹦) o si es mayor ☑️ = 1 y realizamos la operación
*En la comparación de < o > de los números es como si fueran decimales => 0 1 0 = 10.

Ejemplo

    1 0 1 1 0 / 1 0 = 0🌥 1🌤 0 🌞 1 🌧 1☁️ = 1 0 1 1 El cero de la izquierda no se toma
    10 < 1 = >❌ = 🌥 0
    10 < 10 => (﹦) = 1 0 - 1 0 = 0 0 = 🌤1
    10 < 001 => ❌ = 0 🌞
    10 < 11 = ☑️ = 0 0 1 1 - 1 0 = 0 1 = 1 🌧
    10 < 010 => (﹦) = 0 1 0 - 1 0 = 0 0 = ☁️1

![imagen](https://user-images.githubusercontent.com/83564327/191410499-e6277453-effc-4028-9028-c551bf097720.png)

### Tabla de verdad 

Herramienta que nos ayuda a determinar cuales son las condiciones necesarias para que sea verdadero o valido un enunciado propuesto.

TABLA DE LA VERDAD CON BINARIO 

![imagen](https://user-images.githubusercontent.com/83564327/191411667-db816116-d49c-4cce-bddc-15d79e83b681.png)

TABLA DE LA VERDAD 
![imagen](https://user-images.githubusercontent.com/83564327/191411731-20259264-cc38-4ba1-98fe-5131e6f0188e.png)

-Negación: Devulve el valor opuesto de la proposicion considerada

-Conjunción: Es verdadera cuand ambas son verdaderas. 

-Disyunción: sera verdadera cuando por lo menos una de las proposiciones es verdadera, de lo contratio sera falsa 

### Operadores logicos 

Son herramientas que nos permiten entenerder aquellas condiciones que no va a permitir obtener un resultado 

Los operadores lógicos se usan para combinar dos valores Booleanos y devolver un resultado verdadero, falso o nulo. Los operadores lógicos también se denominan operadores Booleanos.

⚡👉Operadores lógicos

Operador “No”: Devuelve True cuando la expresión es falsa. Invierte el valor de una afirmación.
Ejemplo de No: No Luz encendida = Luz apagada. Devuelve el inverso de la expresión.

Operador “Y”: Devuelve True cuando Expresión1 y Expresión2 son verdaderas.
Ejemplo de Y: Expresión1 Y Expresión2 (Ambas expresiones tienen que ser true)

Operador “O”: Devuelve True cuando Expresión1 o Expresión2 es verdadera.
Ejemplo de O: Expresión1 O Expresión2 (Puede ser true una sola expresión o ambas)

Operador “Xor”: Devuelve True si Expresión1 es verdadera o Expresión2 es verdadera, pero no ambas.
Ejemplo de Xor: Expresión1 Xor Expresión2 (Tiene que ser true una sola expresión, no pueden ser ambas, así como tampoco ninguna)


![imagen](https://user-images.githubusercontent.com/83564327/191412703-ec5ed2fc-8bb3-4417-b70a-f09cc2a59b80.png)

### Operadores Aritméticos 

Son elementos o simbolos que nos permiter indentificar cuales son los proceso y resultado dentrode un flujo de trabajo.



Los operadores aritméticos son aquellos que “manipulan” datos numéricos, tanto enteros como reales. Se usan para calcular un valor de dos o más números, o cambiar el signo de un número de positivo a negativo o viceversa.

⚡👉Operadores aritméticos

Operador suma + : Suma dos números.
Ejemplo de suma + : [Subtotal] + [ImpuestoSobreVentas]

Operador resta - : Busca la diferencia entre dos números o indica el valor negativo de un número.
Ejemplo de resta - : [Precio]-[Descuento]

Operador multiplicación * : Multiplica dos números.
Ejemplo de multiplicación * : [Cantidad]*[Precio]

Operador división / : Divide el primer número entre el segundo.
Ejemplo de división / : [Total]/[RecuentoDeElementos]

Operador resto % : Divide el primer número entre el segundo y después devuelve únicamente el resto.
Ejemplo de resto % : [Registradas] % [Salas]

Operador exponente ^ : Eleva un número a la potencia de un exponente.
Ejemplo de exponente ^ : Número ^ Exponente

### Operadores de comparación 

Los operadores de comparación se usan para comparar valores y devolver un resultado que sea True, False o Null.
⚡👉 Operadores de comparación

    Menor que < : Devuelve True si el primer valor es menor que el segundo valor.
    Ejemplos:
    5 < 9 ( true)
    8 < 2 (false)

    Menor o igual <= : Devuelve True si el primer valor es menor o igual que el segundo valor.
    Ejemplos:
    7 <= 14 (true)
    7 <= 7 (true)
    7 <= 5 (false)

    Mayor que > : Devuelve True si el primer valor es mayor que el segundo valor.
    Ejemplos:
    9 > 6 ( true)
    8 > 19 (false)

    Mayor o igual >= : Devuelve True si el primer valor es mayor o igual que el segundo valor.
    Ejemplos:
    12 => 8 (true)
    12 => 12 (true)
    12 => 25 (false)

    Igual = : Devuelve True si el primer valor es igual al segundo valor.
    Ejemplos:
    15 = 15 (true)
    15 = 11 (false)
    15 = 29 (false)

    Diferente <> : Devuelve True si el primer valor no es igual al segundo valor.
    Ejemplos:
    14 <> 17 (true)
    14 <> 123 (true)
    14 <> 14 (false)

Nota: El operador diferente <> se suele representar como != en lenguajes de programación.

### Reto 0: Identidica los operadores 

👉 Ejemplos de uso

Ejemplos con decimales:

7 < 10 AND 10 => 10 AND 12 > 6 
(true, ya que todas las condiciones devuelven un valor verdadero)

8 < 4 OR 31 <= 10 OR 5 > 6 
(false, ya que todas las condiciones devuelven un valor falso. Ninguna se cumple)
   
8 < 4 XOR 45 > 43 (true, ya que se cumple una sola condición.)

Ejemplos con situaciones de la vida real:

-Para ducharme necesito agua AND jabón (true, ya que ambos elementos son indispensables para ducharme)

-Puedo tomar mis curso de platzi desde mi móvil OR mi computadora (true, porque la plataforma está tanto en aplicación móvil como en la web)
 
-Quiero una golosina, puedo comer chocolates XOR caramelos. El médico me recetó estrictamente comer solo una golosina al día, así que me decido por el chocolate (true, porque solo podía elegir entre uno o otro, pero no ambos).

“Porque, recuerda!.. las preguntas correctas nos van a ayudar a encontrar el resultado y a tomar las decisiones que estamos necesitando tomar, parece simple… pero al hacer esta expresión grafica de nuestros operadores y de las herramientas que tenemos a la mano vamos a encontrar mucho mejor aquellas respuestas que estamos buscando” 

Ana Belisa Martínez

### Agoritmos 
🌈 ¿Cómo construir un algoritmo? 🌈

Tener claro el requerimiento: quiero encender la luz de la habitación donde estoy en este momento

✨ Análisis ✨
    ¿Cuál es el objetivo? -> Encender la luz 💡
    ¿Con qué recursos cuento? -> Habitación 🚪
    ¿Qué condiciones previas deben pasar para que sea posible? -> Que la luz esté apagada

✨ Paso a paso ✨

¿Qué tiene que pasar para que se cumpla el objetivo con los recursos que tengo?

a. Validar que la luz esté apagada (condición base)
b. Identificar dónde voy a encender la luz
c. Presionar el elemento que me permita encender la luz

¿Si yo realizo estos pasos cumpliré con el objetivo?
Validar si el resultado que obtuve fue el que esperaba inicialmente

✨ Optimizar ✨
a. Tomar el requerimiento
b. Identificar qué tenemos y lo que no
c. Qué condición hace falta para que suceda
d. Lo que necesitamos para que el objetivo se logre

🎯 Identificar las diferentes alternativas que puedo tomar para cumplir el objetivo

### Diagrama de flujo 

Conjunto de símbolos y de elementos que nos permiten representar cada uno de los pasos que componen un proceso. Siempre identificar lo pasos. 

✨ Elementos ✨

🔴 óvalo horizontal - Inicio y fin
🔹 Decisión: pregunta cuya respuesta debe ser sí o no
🟧 rectángulo - Proceso: operación, mensaje o algoritmo
➡️ Conectores: inicio y final de un proceso

![imagen](https://user-images.githubusercontent.com/83564327/192123365-dd7ff687-2c69-4356-9fa7-a76857e6af24.png)

# Manejo de datos, estructuras y funciones 

### ¿Qué es un dato? 

Es una porción de información muy concreta y especifica que nos permite, a través de diferentes operaciones y estructuras, tomar decisiones. Hacen parte de un algoritmo en una estructura más grande.

Son la base sobre la cual partimos y sobre la cual llegamos, además, componen todas las estructuras para que puedan funcionar y sean operables.

### ¿Qué es una concatenación?

En la unión de alguna variable o en este caso una cadena de texto del mismo tipo de texto, al momento de concatenar los espacios no se agregan automáticamente, tienes tu que realizarlo manualmente

## Tipos de datos 

#### Texto 

Estan compuesto por letras principalmente. Son estos tipos de datos al que le llamamamos cadenas de caracteres, aquel que esta compuesto por una secuencia de letras y no necesariamente deben tener un significado. 

Ejemplo: 

            Ana 

Los espacios en la frase también forman parte de la cadena texto. Son fundamentales 

        Ana_esta_estudiando 
        
Todas las oraciones son una cadena de texto, un caracter es solo un unidad de de cada una de la letras que forma una cadena de caracteres 

Podemos tener 2 cadenas de texto separadas y unirlas mediante la concatenación.
Para concatenar necesitamos que ambas partes sean del mismo tipo de dato, en este caso de tipo texto.

        Parte1: Ana
        Parte2: está 
        Concatenación: Anaestá

Para que nuestra cadena de texto tenga sentido lógico es necesario concatenar un espacio
        
        Parte1: Ana
        Parte2: _ (el guion bajo es solo para representar el espacio)
        Parte3: está
        Concatenación: Ana está

Al momento de definir tu tipo de dato como texto, todo lo que incluya tu cadena será reconocido como texto, incluso si su representación gráfica es un número, por ejemplo, un nombre de usuario: “user2004” <–es una cadena de texto.


### Númericos 

Esta representado por los numero que conocenos dia a dia que nos ayuda a trbaajar co nuestro operadores aritmeticos 

Int o entero: Incluye los números sin ningún tipo de adición decimal.

        7
        10
        20 
        
Float o double: Incluye los números con parte decimal.

        3,14
        29,23
        37,73
        
Los datos numéricos en combinación con los operadores aritméticos nos permite realizar diferentes operaciones matemáticas y guardan cierta relación con los tipos de datos de texto.

Pueden también estar representados con unidades negativas

    -7
    -10
    +20
       
Concatenación: Te permite combinar los elementos 


En python sería así:

                number = '123'
                text = 'HolaMundo'
                cont = text + number
                print(cont)
 
### Booleanos 

Son aquellos que estan representado por true o false, o 1 y 0, o si o no. no permiten identificar cuando algo en negativo o positivo, cuando hay presencia o cuando hay ausencia de algo. Son resultado dentro de un flujo o un procesos que nos permiten tomar dicisiones. 

![imagen](https://user-images.githubusercontent.com/83564327/192148511-58945d1e-5a56-49fe-9885-27182a1adbde.png)


### Arrays 

De manera grafica es un contenedor con pequeñas cajas que cada una de ella es un espacio disponiblee para un dato distinto, que no estaria concatenados, y tampoco estarian operados, y tampcoo un punto para tomar decision, pero puede ir junto e estar separados. 

Un arrays es un contenedor que te permiter tener espacio para tener diferente tipos de datos. Que puede convivir perfectamente. Se empieza a contar de 0 

![imagen](https://user-images.githubusercontent.com/83564327/192148840-86ac7fc9-5d03-4a77-9c80-7ab1e531baee.png)

### Estructuras de control 

Sentencia de control o estructura de control son la que nos permiten controlar las  decision y funcionamiento en nuestro algoritmnos, utilizan los operadores y tipos de datos y concetan todas estas secuencia logicas para crear un algormitmo tal como lo esperamos 

### Condicionales 

No permiten tomar decision a partir de una comparaciones. Ejemplos: 

                If/else 
                Switch 
                Try/Catch 
                
### Ciclos 

Realiza diferente iteraciones de acuerdo a condiciones y situaciones que nuestro algoritmo no este pidiendo

            For 
            While 
            Do While 
            
## Condicionales 

### If y switch 

Ambos no permiten tomer decisiones de acuerdo al resultado de una compración, ejemplos is se cumple o no 

Condicional if: Se usa para tomar decisiones, este evalúa una operación lógica, es decir una expresión que de como resultado True o False. Si la condición devuelve un true se ejecutarán ciertas instrucciones.

            If 3 > 2  
                " 3 es mayor a 2" 
                
Condicional else: Si no se cumple ninguna condición se ejecutará otro bloque de instrucciones

                if 12 < 19 entonces   <--(false)
                    "Es mayor a 19"
                else <--(Se ejecutará el siguiente bloque, ya que la primera condición no lo hizo)
                    "No es mayor que 19"
                
Condicional switch: La estructura selectiva switch selecciona una de entre múltiples alternativas. Esta estructura es especialmente útil cuando la selección se basa en el valor de una variable simple o de una expresión simple denominada expresión de control o selector.
Default: Sirve para que el flujo de nuestro algoritmo no se rompa en caso de que no se cumpla ningún case, mostrando un mensaje por defecto.

                "Se solicita número del 1 al 4"

                 switch (número)
                 
                 case 1:
                  "El número ingresado es 1"
                 case 2:
                  "El número ingresado es 2"
                 case 3:
                  "El número ingresado es 3"
                 case 4:
                  "El número ingresado es 4"
                 default: 
                "El número ingresado no está en el rango 1-4"
                
Ejemplo: 

![imagen](https://user-images.githubusercontent.com/83564327/192150450-2033826f-2417-4ca4-af85-6a70e63dcf24.png)

## Algoritmos con variables y condiciones 

![imagen](https://user-images.githubusercontent.com/83564327/192150589-152f79de-cec3-4457-8e3e-1dc8a5ece673.png)

Edad = 25

if Edad > 18: 
    print ("Es mayor de edad")
else: 
    print("Es menor de edad")
    
## Ciclos 

Un bucle o ciclo, es una secuencia de instrucciones de código que se ejecuta repetidas veces, hasta que la condición asignada a dicho bucle deja de cumplirse.

Ciclo for:

Punto de partida, muy importante
Cantidad de iteraciones. Cantida de vueltas 
Incremento. Sera aquel que aumenta la cantidad 

        let estaturas = [1.80, 1.66, 1.75]

        for ( i=0; i<=2; i++)
        if(estaturas[i]>=1.70{
                console.log("Puedes entrar");
            }else{
                console.log("No puedes entrar");
            }
        }

Ciclo while:

Primero establece la condición para que sucesan las iteraciones.
Mientras un suceda un evento determinado el ciclo seguirá iterando.

            let estaturas = [1.80, 1.66, 1.75]
            let i=0;
            while(i<=2){
                if(estaturas[i]>=1.70){
                     console.log("Puedes entrar");
                }else{
                    console.log("No puedes entrar");
                }  
                i++;
            }
Do while:

Primero ejecuta una instrucción mientras se cumpla una condición.

                let estaturas = [1.80, 1.66, 1.75]
                let r=0;
                do{
                    if(estaturas[i]>=1.70){
                         console.log("Puedes entrar");
                    }else{
                        console.log("No puedes entrar");
                    }  
                    i++; 
                }while (i<=2)
  
### Algoritmos con ciclos 

![imagen](https://user-images.githubusercontent.com/83564327/192153221-a7af8413-bc33-4a8c-ac80-9ae6556b1f30.png)


## Try Catch 

La declaración try...catch señala un bloque de instrucciones a intentar (try), y especifica una respuesta si se produce una excepción (catch).

Ejemplo: 

        try {
          nonExistentFunction();
        } catch (error) {
          console.error(error);
          // expected output: ReferenceError: nonExistentFunction is not defined
          // Note - error messages will vary depending on browser
        }


### Algoritmo con manejo de errores 

Division 

Sin try/catch:

            a = 10
            b = 0

            c = a / b

            print("El resultado de dividir " + a + " entre " + b + " es " + c)
            print("El programa termino con exito")

En este caso, la ultima linea de código, el mensaje que debería salir con El programa termino con exito no se ejecuta ya que Python al tratar de dividir por 0 lanzará un error en la consola y detendrá la ejecución del código.

Con try/catch

                a = 10
                b = 0
                
                try:
                    c = a / b
                    print("El resultado de dividir " + a + " entre " + b + " es " + c)
                except:
                    print("Alto, no es posible dividir por 0")
                
                print("El programa termino con exito")

En este caso, Python al tratar de realizar la división por 0 lanza el except (En Python no es catch sino except pero el concepto es el mismo), y muestra el mensaje Alto, no es posible dividir por 0, luego continúa con el código y finalmente muestra el mensaje El programa termino con exito que está fuera del bloque de try/catch.

Espero que el aporte les sea de ayuda para entender un poco más el concepto de try/catch. Otros usos que se le puede dar a esta instrucción, es cuando tratas de realizar operaciones artiméticas con diferentes tipos de datos que no son compatibles, cuando alguna variable no está definida, cuando se trata de indexar algún valor que no está en un array y así hay muchos otros usos para esta instrucción. San Google siempre será de gran ayuda si necesitan ampliar el concepto. 


## Función

Función: Una función es un bloque de instrucciones que hace una actividad especifica de forma independiente al resto del algoritmo. Con una función puedes segmentar partes de tu algoritmo, las cuales puedes reutilizar.

Una función tiene 3 componentes importantes:

- Los parámetros, que son los valores que recibe la función como entrada (puede             llevarlos o no, pero en la mayoría de casos si lleva).

- Las instrucciones de la función, que son las operaciones que hace la función.

- El resultado (o valor de retorno), que es el valor final que entrega la función.


Ejemplo: 

            function sumar(a, b) {
                    return console.log(a+b);
                }
                suma(1,2);
               
## Scope o alcance en funciones

Privadas: Funcionan de forma local, no pueden ser llamadas en otros algoritmos, por eso es importante determinar el alcance de la función, ya que puedes estar tratando con información más compleja que es especifica para ese algoritmo, y no puede ser compartida a otros algoritmos que la puedan necesitar.

Públicas: El alcance es global. Puedes mandar a llamar funciones de un algoritmo a otro.

![imagen](https://user-images.githubusercontent.com/83564327/192162873-c05db40d-5ef7-4b21-8828-9889b9fbccd0.png)

¿Qué es el scope en JavaScript?

El scope puede definirse como el alcance que una variable tendrá en tu código. En otras palabras, el scope decide a qué variables tienes acceso en cada parte del código. Existen dos tipos de scope, el scope global y el scope local. A continuación te mostraré un par de ejemplos explicando en qué consiste cada uno de ellos.
Qué es el Scope Local

Cuando puedes acceder a una variable únicamente en cierta parte del código, se dice que esa variable está declarada en el scope local. Estas también son conocidas como variables locales. Un ejemplo de esto es cuando una variable está declarada dentro de un bloque o una función. Si tratas de acceder a esta variable fuera de esta función o bloque, tendrás un error que dirá que la variable no está definida.

                function platzi() {
                	const soyEstudiante = true;
                	console.log(soyEstudiante);
                }
                
                platzi(); // true
                console.log(soyEstudiante); // soyEstudiante is not defined

Qué es el Scope Global

Se dice que una variable está en el sope global cuando está declarada fuera de una función o de un bloque. También son conocidas como variables globales. Puedes acceder a este tipo de variables desde cualquier parte de tu código, ya sea dentro o fuera de una función.

                const soyEstudiante = true;
                
                function platzi() {
                	console.log(soyEstudiante);
                }
                
                platzi(); //true
                console.log(soyEstudiante); //true

A pesar de que JavaScript nos permite declarar una variable como global, no es una buena práctica. Una de las razones es porque tenemos la posibilidad de declarar dos variables globales en distintas partes del código con el mismo nombre sin notarlo.
