# TALLER 2: DISEÑO Y ESTRUCTURACIÓN DE APLICACIONES DISTRIBUIDAS EN INTERNET

Aplicación web diseñada para acceder a los recursos (imágenes y páginas html) ubicados en una ruta especificada.

### Prerrequisitos

- Java
- Maven
- IDE

### Instalación

1. Clonar el repositorio

```
https://github.com/jloading/Taller2AREP
```

2. Se construye el proyecto con Maven

```
mvn package
```

3. Se ejecuta el proyecto con el comando (asegúrese de copiar y pegar el comando en su terminal)
```
mvn exec:java -Dexec.mainClass="edu.escuelaing.app.HttpServer"
```

4. Para acceder a los recursos especificados se debe escribir en el navegador cualquiera de las siguientes direcciones

```
http://localhost:35001/escuelaing.png
```

```
http://localhost:35001/Mac.jpg
```

## Corriendo las pruebas

Se acceden a los recursos especificados, en este caso son dos imágenes:

<img width="721" alt="Captura de pantalla 2023-08-30 a la(s) 9 02 03 p m" src="https://github.com/jloading/Taller2AREP/assets/65261708/de607ae4-fe93-4825-8fe2-410febdf4b43">
<img width="720" alt="Captura de pantalla 2023-08-30 a la(s) 9 02 26 p m" src="https://github.com/jloading/Taller2AREP/assets/65261708/436295ba-f81d-4e6a-a470-f6da65ac0840">


## Hecho con

* Java
* Git
* Maven
* HTML, JavaScript

## Autor

* **Juan Carlos Acosta**

