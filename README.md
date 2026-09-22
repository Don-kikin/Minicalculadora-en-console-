# Calculadora Básica en JavaScript (Entorno Web)

Un script funcional que interactúa con el usuario a través de cuadros de diálogo nativos del navegador para capturar datos numéricos y realizar las cuatro operaciones aritméticas fundamentales.

## Características

* Captura de texto mediante la función `prompt()`.
* Conversión explícita de tipos de datos (de *String* a *Number*).
* Definición de funciones modulares para cada operación matemática:
  * Suma
  * Resta
  * Multiplicación
  * División
* Salida de resultados estructurada a través de la consola del desarrollador.

## Requisitos Previos

* Un navegador web moderno (Chrome, Firefox, Edge, Safari).
* Acceso a las Herramientas de Desarrollador (DevTools) del navegador.

## Ejecución del Código

Dado que el script utiliza `prompt()`, este **no puede** ejecutarse mediante Node.js en una terminal estándar. Para probar el código:

1. Abre tu navegador web preferido.
2. Abre la consola de desarrollador (usualmente presionando `F12` o `Ctrl+Shift+J` en Windows / `Cmd+Option+J` en Mac).
3. Copia el contenido del script y pégalo directamente en la consola.
4. Presiona `Enter` para iniciar la ejecución.

## Uso

1. El navegador mostrará un cuadro de diálogo solicitando tu nombre. Introdúcelo y presiona Aceptar.
2. El script imprimirá un saludo personalizado en la consola oculta.
3. A continuación, el navegador lanzará dos cuadros de diálogo consecutivos solicitando el "numero" y el "numero2".
4. Ingresa valores numéricos válidos en ambos.
5. Revisa la consola del navegador; el sistema habrá impreso los resultados secuenciales de la suma, resta, multiplicación y división de los números ingresados.
