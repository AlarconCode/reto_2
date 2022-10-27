- PASOS NECESARIOS PARA SUBIR UN ARCHIVO AL SERVIDOR REMOTO GIT

Una vez tenemos clonado el repositorio remoto de github en nuestra maquina local los pasos para subir los archivos que añadamos o modifiquemos en local al servidor remoto son:

1.- utiliar comando git status para comprobar que archivos han sido modificados o creados.

2.- Después usamos el comando git add nombreDelArchivoModificado.js o git add . para pasar los archivos al stage o staging area.

3.- Volvemos a comprobar el status con git status, vemos como nos indica que los cambios estan listos para ser commited, es decir listos para ser confirmados, esto lo hacemos con el comando git commit le añadimos el flag -m para escribir  un mensaje descriptivo de los cambios que hemos realizado, tambien podemos incluir el mombre del archivo si queremos hacer commint solo de un archivo.

4.- Una vez hacemos commit los archivos pasan ha estar confirmados y listos para sincronizarse con el servidor Git haciendo uso el comando git push