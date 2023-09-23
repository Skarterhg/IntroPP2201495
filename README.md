# IntroPP22014

El archivo analizado lleva por nombre "matrixmul.cpp", en el cual se realiza un ejercicio de multiplicacion de matrices en paralelo y en secuencial, para analizar los resultados de tiempo obtenidos.
# Ejecucion

Para ejecutar el codigo en guane, es necesario crear un archivo de texto, para este caso utilizaremos vim, con el siguiente comando:

    vim matrixmul.cpp

Despues se pega el codigo que ejcuta la operacion y se guarda el archivo

Posteriormente se ejecuta el siguiente comando:

    g++ -Wall -fopenmp matrixmul.cpp -o matrixmul

El cual nos permitira utilizar el compilador de c++ y nos pueda mostrar el registro de errores (En caso de haberlos), además de crear el archivo ejecutable

Para correr el ejecutable anteriormente creado se corre el siguiente comando:

    ./matrixmul

Con esto podemos ver el resultado de la ejecucion de el codigo de multiplicacion de matrices.

Si se desea altera el tamaño de las matrices, se debe modificar en el codigo en el editor de texto *vim*
