# Instrucciones_Practicas

## Descargar el código del proyecto

Para poder utilizar el autocorector en las prácticas de CORE, es necesario utilizar la **versión 16 de Node.js, superior a 16.8 (https://nodejs.org/es/) y Git (https://git-scm.com/)**.
El proyecto debe clonarse en el ordenador en el que se está trabajando:

```
$ git clone https://github.com/CORE-UPM/PX_nombre_de_la_practica
```

A continuación se debe acceder al directorio de trabajo, e instalar todas las dependencias.

```
$ cd PX_nombre_de_la_practica
$ npm install
```


## Pruebas con el autocorector

Para ayudar al desarrollo, se provee una herramienta de autocorrección que prueba las distintas funcionalidades que se piden en el enunciado. Para utilizar esta herramienta debes tener node.js (y npm) (https://nodejs.org/es/) y Git instalados.

Para instalar y hacer uso de la herramienta de autocorrección en el ordenador local, ejecuta los siguientes comandos en el directorio raíz del proyecto:

```
$ npm install autocorector     ## Instala el programa de test
$ npx autocorector             ## Pasa los tests al fichero a entregar
............................   ## en el directorio de trabajo
... (resultado de los tests)
```

Se puede pasar la herramienta de autocorrección tantas veces como se desee sin ninguna repercusión en la calificación.

## Pruebas manuales y capturas de pantalla

Es importante desarrollar la práctica viendo poco a poco el resultado y visualizando cada cambio introducido hasta que funcione. Considerando los test provistos por el autocorector como una serie de requisitos “estrictos” o “estáticos” como por ejemplo que un elemento tenga determinado id o que haya determinados textos en la aplicación.

No se recomienda por lo tanto ir desarrollando sin visualizar lo que hacemos y pasar el autocorector a cada paso “a ver si se consiguen los puntos”, porque los errores que dan las baterías de tests son más crípticos que lo que veremos en el navegador o en la consola por nosotros mismos al ejecutar la práctica.

Adicionalmente a pasar la batería de tests y obtener un 10/10 hay que hacer dos capturas de pantalla con la práctica completa, es decir en la versión final antes de entregar. Dichas capturas se tienen que ubicar en formato png, jpg o pdf en el directorio “miscapturas”. Y el autocorector las subirá junto con el código de la práctica y el resto de evidencias a Moodle. Estas capturas son obligatorias y deben ser personales, en ellas se debe ver que lo ejecutado coincide con lo entregado en el código. Estas capturas serán revisadas por el profesor para comprobar que se ha realizado la funcionalidad correctamente.

En el enunciado de cada práctica se especificará qué capturas concretas deben subirse.

## Instrucciones para la Entrega y Evaluación.

Una vez satisfecho con su calificación, el alumno puede subir su entrega a Moodle con el siguiente comando:

```
$ npx autocorector --upload
```

La herramienta de autocorrección preguntará por el correo del alumno y el token de Moodle. 
En el enlace **https://www.npmjs.com/package/autocorector** se proveen instrucciones para encontrar dicho token.
