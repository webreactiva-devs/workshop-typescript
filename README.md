> Taller en directo con suscriptores de Web Reactiva para aprender las características principales del lenguaje TypeScript.

ㅤ

## ¿Por qué TypeScript?

TypeScript compila (transpila) en código JavaScript añadiéndole algunas ventajas de peso:
1. Tipado de datos
2. Autodocumentación
3. Interfaces de datos

Quizás esto te diga poco, pero expresado de esta otra forma te ayude:
1. Evitar que los “undefined” inesperados en producción arruinen tu sábado noche
2. No tener que navegar por la documentación para saber que método utilizar
3. Tener confianza en que si anda como un pato y hace _cuac_ como un pato sea un pato (y no un _undefined_ o un _pantallazo en blanco_)

ㅤ

## 🔎 Objetivos prácticos
- Dedicar algo más de 60 minutos a aprender las bases del lenguaje
- Tener la posibilidad de preguntar dudas en directo
- Poner las manos sobre el teclado y sacar medio c\*ulo fuera de la silla

**¿Dónde me apunto?**
Tienes que ser suscriptor premium de Web Reactiva

ㅤ

## 🛠¿Cómo funciona el taller?

- Tendremos una primera sesión online en directo el 9 de Febrero a las 19:00 CET (en punto ;)
- El ponente (Dani) irá explicando conceptos y proponiendo ejercicios que estarán en este repositorio
- Cada asistente podrá resolverlos en su propio ordenador.
- Es OBLIGADO tener a punto los requisitos para empezar el taller (leer aquí abajo)

ㅤ

## ✅ Requisitos para empezar el taller

Para ser más ágiles te propongo unos sencillos pasos para tener todo a punto en tu ordenador antes de comenzar el taller.

⏰ 5-10 minutos.

ㅤ

### 1. Editor de código

Usaremos Visual Studio Code para la explicación.

👉 Si no quieres usar VSC, el [playground online de TypeScript] puede ser de ayuda.

ㅤ

### 2. TypeScript instalado globalmente

Seguiremos la recomendación de instalar globalmente TypeScript. 

(Debes tener instalado node.js en tu ordenador)

Para la instalación ejecuta en la terminal (da igual la carpeta)

`npm install -g typescript`

📝 El modificador `-g` indica que es una instalación global.

Lanza este comando y verás la versión instalada

`tsc --version`

En mi caso `Version 4.9.5`

👉 Aquí explican [como instalarlo] en detalle

ㅤ

### 3. Primera ejecución de código

Para comprobar que todo esta en orden sigue estos pasos:

1. Crea una nueva carpeta en tu ordenador y llámala `taller-typescript`
2. Abre la carpeta en Visual Studio Code
3. Crea un fichero con el nombre `start.ts` y copia este código dentro: `let message: string = 'Hola Malandriner'; console.log(message);
4. En la consola de VSC o en tu terminal (dentro de la carpeta `taller-typescript`) ejecuta este comando: `tsc start.ts` (En Windows `tsc .\start.ts`)
5. Te debería aparecer un fichero `start.js` en la misma carpeta.
6. Ejecuta `node start.js` y verás el saludo en la terminal.

👉 Aquí más detalles sobre el [uso con Visual Studio Code]


**¡Estas listo\a para empezar!** 🥳
