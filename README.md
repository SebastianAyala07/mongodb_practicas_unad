## Puesta en marcha

----

__Para poner en marcha estas sentencias de mongodb se debe tener instalado docker, docker-compose, vscode. Y en vscode se debe instalar la extension llamada 'MongoDB for VS Code'.__

_Se debe crear una carpeta que se llame 'mongo_data' para realizar la persistencia de la informacion contenida en la base de datos, dado el escenario en el que bajemos el contenedor temporalmente._

_Una vez se tienen estos requerimientos, se debera ejecutar el siguiente comando en la consola._

```
$ docker-compose up -d
```

__Nota: Puede variar en diferentes sistemas operativos. Actualmente las instrucciones son realizadas en un SO (Ubuntu 22.04)__

---
_Una vez hecho esto se podra gestionar la conexion a bd por medio de la extension de vscode 'Mongodb for vs code' y posterior a esto ejecutar las sentencias de cada uno de los archivos._
