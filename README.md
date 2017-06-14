# Algoritmos para la conjetura de Peres

*Alberto Solís Encina. Proyecto fin de carrera 2010-2011. Departamento de Matemática Aplicada I

Guía para obtener los ficheros fuente (en .c) del algoritmo de Peres para usar en Nauty.
1. Descomprima el contenido en una carpeta (con el nombre "AlgPeresDimN", por ejemplo).
2. Ejecutar el Script "scriptgen.sh" y seguir los pasos que se indiquen.
3. Se obtienen los códigos generados en la misma carpeta y con los nombres indicados en la ventana de información del script, son:
			"AllInKn.c"
			"numberKn.c"
			"AlgPeres.c"
			"AlgPeres.h"
4. Añadir a la carpeta de Nauty los ficheros anteriormente mencionados y los ficheros "makefile" y "TestCOLg" que venían en el comprimido.
5. Abrir un terminal de consola y situarse en el directorio de Nauty.
6. Ejecutar:
			"./configure"
			"make"
7. Ya pueden utilizarse las funciones del algoritmo de Peres y adicionalmente una función "AllInKn" que dice si dado un grafo todo vértice está contenido en al menos un Kn, siendo n la dimensión que se indicó para la generación del algoritmo de Peres.
	
  Usando :  "./countg -help" se indican las posibilidades
	Originalmente se ha asignado la opción "-A" para la ejecución del algoritmo de Peres y "-P" para la función "AllInKn".			
