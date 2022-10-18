# Herramientas de desarrollo



2. Para cada uno de los lenguajes anteriores, indica el proceso realizado para conseguir ejecutar el código: bash: interpretación¿compilación o interpretación?

python: interpretación

php: interpretación

javascript: interpretación

c: compilación 

c++: compilación

java: compilación 

ruby: interpretación 

go: compilación

rust: compilación

lisp: compilación

nasm: compilación



3. Para cada uno de los lenguajes anteriores, indica el nombre del compilador o intérprete utilizado en GNU/Linux.

bash: SHELL

python: GNU Readline

php: Software libre 

javascript: Software libre

c: gcc 

c++: cc

java: javac

ruby: IRB

go: go build

rust: rustc

lisp: ABCL

nasm: ensamblador



4. Investiga y averigua qué extensión tienen los archivos de código fuente de los siguientes lenguajes:

bash: .sh 

python: .py

php: .php

javascript: .js

c: .c

c++: .cc

java: .java

ruby: .ruby

go: .go

rust: .rs

lisp: .lisp

nasm: .asm

6. ¿Qué extensión tienen los archivos de código objeto?

Los archivos de objeto ( cuya extensión es .obj) son archivos intermedios generados por el compilador antes de crear un ejecutable. El archivo de objeto consiste de una tabla de símbolos y el código C compilado en código de máquina. La tabla de símbolos contiene una lista de funciones y la dirección del archivo objeto en donde se localiza el código para esa función en particular. Todos los compiladores generan los archivos objeto de diferente manera. El ligador es responsable de manipular las llamadas a funciones que se encuentran fuera del archivo de código C que ha sido compilado; busca las referencias a esas funciones en las tablas de símbolos de todos los archivos objeto que están disponibles. Si las referencias son encontradas, se ligan con el código, si no, se genera el error Undefined Symbol.



11. Define qué se entiende por biblioteca o librería y los tipos que existen.

Una biblioteca es un conjunto de archivos que se utiliza para desarrollar software. Suele estar compuesta de código y datos, y su fin es ser utilizada por otros programas de forma totalmente autónoma. Simple y llanamente, es un archivo importable. 

Hay dos tipos de bibliotecas en programación, las dinámicas y las estáticas. Las estáticas se graban en un programa como ejecutables y sirven exclusivamente para eso, luego se puede borrar sin problemas. Las dinámicas no se copian en el programa al compilaralas, las subrutinas son cargadas en tiempo de ejecución, en vez de enlazarse en tiempo de compilación. 



12. ¿Qué tipo es el más utilizado actualmente? ¿Por qué?

Las bibliotecas dinámicas, porque utilizan recursos independientes al ejecutable que las llama. Es decir, no es copiada al programa durante el proceso de compilación.



15. Busca información y explica las ventajas y desventajas de usar bibliotecas estáticas.

Ventajas: Las bibliotecas estáticas resisten la vulnerabilidad porque viven dentro del archivo ejecutable. La velocidad en tiempo de ejecución se produce más rápido porque su código objeto está en el archivo ejecutable. Por lo tanto, las llamadas realizadas a las funciones se ejecutan más rápido. Recuerde, la biblioteca dinámica vive fuera del ejecutable, por lo que las llamadas se realizan desde el exterior del ejecutable.

Desventajas: Los cambios realizados en los archivos y el programa requieren volver a enlazar y recompilar. El tamaño del archivo es mucho mayor.



16. Busca información y explica las ventajas y desventajas de usar bibliotecas dinámicas.

Ventajas. Solo necesita una copia en tiempo de ejecución. Depende de que la aplicación y la biblioteca estén estrechamente disponibles entre sí. Varias aplicaciones en ejecución utilizan la misma biblioteca sin necesidad de que cada archivo tenga su propia copia. Están vinculadas en tiempo de ejecución. No requiere recompilación y volver a enlazar cuando el programador realiza un cambio.

Desventajas: Si la biblioteca dinámica se daña el archivo ejecutable puede no funcionar porque vive fuera del ejecutable y es vulnerable a la rotura. Contienen archivos más pequeños.