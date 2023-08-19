# Actividad 1: Exoplanetas

_Activity based on the Exoplanets Course given by Y. Gómez (UNAM) at the 43th International School for Young Astronomers (ISYA 2023 - Puebla, México). Modified by L. Cano for the PMS Astronomy Club (UMSA-Bolivia)_

En este repositorio encontrarán información necesaria para realizar la actividad de Exoplanetas. La cual será la sesión inicial del semestre para el Club.

## Introducción
En esta actividad aprenderemos un poco del método más didáctico para descubrir exoplanetas, el tránsito, en el cual el planeta pasa por en frente de la estrella, ocultando algo de su luz. Usando esos datos podemos saber más del mismo planeta, hasta incluso descubrir sus propiedades físicas. Realizaremos simulaciones para entender las ventajas y limitaciones de este método a comparación de otros. Finalmente intentaremos realizar un ajuste de modelo a un sistema conocido para conocer cómo se utilizan estos datos en la vida real. 

![An exoplanet transit](https://www.esa.int/var/esa/storage/images/esa_multimedia/images/2003/06/planet_transit/9798645-3-eng-GB/Planet_transit_pillars.jpg)

Es posible que realicemos un fitting a data con librerías o capaz con métodos estadísticos, es muy posible que esto se haga en otra sesión o sea un proyecto estudiantil de semestre.

## Pre-requisitos
Para realizar esta actividad necesitarán contar con un ordenador, pueden compartir el mismo hasta entre 2 personas. Usaremos un código desarrollado por la autora del material y una librería muy específica para modelar las curvas de luz. Una segunda actividad (por confirmar) será un análisis de databases que no necesita muchos requisitos computacionales como la actividad 1.

### 1. Ordenador
Necesitarán una computadora, y habrá dos formas de trabajar.

 * **LOCAL:** Trabajando "offline", deberán haber descargado todo el material necesario, la ventaja es que no se necesita conexión a internet. La desventaja es que la librería _batman_ no es fácil de instalar en Windows, por lo que esta opción está habilitada solamente para computadoras con Sistema Operativo Linux y/o MacOS. En caso de querer trabajar de esta forma contactarme lo antes posible para guiarles con la instalación.
 
 * **NUBE:** Gran ventaja, no necesitan instalar NADA. Usaremos Google Colab, que es un laboratorio virtual para utilizar los códigos. Para eso deberán descargar el material y subirlo en una carpeta de Drive (en sus propias cuentas). Al estar enlazado, Colab no necesita más. La desventaja es que sí necesitarán una conexión estable durante la actividad (algo que no podemos asegurar por el mal wifi en el campus), se recomienda que compren una bolsa ilimitada de megas o consigan algún otro medio de conexión.
 
## 2. Materiales
`lab_transiting_exoplanets.ipynb`. Archivo jupyter notebook que tiene todos los materiales necesarios para el manejo de este laboratorio.

## 3. Lecturas previas y bibliografía
 + [Down in Front!: The Transit Photometry Method](https://www.planetary.org/articles/down-in-front-the-transit-photometry-method)
 + [Transit Method: Las Cumbres Observatory](https://lco.global/spacebook/exoplanets/transit-method/)
 + [batman: BAsic Transit Model cAlculatioN in Python. Laura Kreidberg 2015 PASP 127 1161](https://iopscience.iop.org/article/10.1086/683602)
 
Artículo si quieren profundizar más en cómo se calcula analíticamente las curvas de luz.
 + [Analytic Light Curves for Planetary Transit Searches. K. Mandel and E. Algon 2002 ApJ 580 L171](https://iopscience.iop.org/article/10.1086/345520)



## 4. Librerías
Todo el código descrito es parte de las librerías consiguientes, todos los créditos correspondientes a sus autores.

### 4.1. Librería batman
La librería que utilizaremos se llama batman: Bad-Ass Transit Model cAlculatioN
[github](https://github.com/lkreidberg/batman)

### 4.2. Pytransit
Librería alternativa para modelar las curvas de luz. No es tan sencilla de instalar pero sí se logré instalarla en Windows.

-----
_Este documento aún está en proceso de construcción y será actualizado paulatinamente._
