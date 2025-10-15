# Calculadora con Vanilla JavaScript

Este proyecto es una calculadora básica desarrollada con **HTML**, **CSS** y **JavaScript (Vanilla)**. Permite realizar operaciones aritméticas simples como suma, resta, multiplicación y división.


## Descripción
La calculadora tiene una interfaz sencilla con un campo de entrada (`input`) que muestra los números y resultados, y botones para dígitos (0-9), operadores (+, -, *, /), un botón para calcular el resultado (=) y un botón para limpiar la pantalla (C). Todo el comportamiento está implementado con JavaScript puro, sin dependencias externas.

## Características
- Operaciones básicas: suma, resta, multiplicación y división.
- Interfaz responsiva gracias a la metaetiqueta `viewport`.
- Botón de limpieza para reiniciar la calculadora.
- Diseño simple y funcional con CSS personalizado.
- Entrada de números y operadores a través de botones.

### Archivos Principales
- **`index.html`**: Contiene la estructura de la calculadora, con un campo de entrada (`<input id="display">`) y botones para dígitos y operadores.
- **`styles.css`**: Define los estilos de la calculadora, como la disposición de los botones y el diseño del campo de entrada.
- **`index.js`**: Implementa las funciones para:
  - Agregar números y operadores al campo de entrada (`appendToDisplay`).
  - Calcular el resultado de la expresión (`calculate`).
  - Limpiar la pantalla (`clearDisplay`).

## Cómo Usar
1. Ingresa números haciendo clic en los botones de dígitos (0-9).
2. Selecciona un operador (+, -, *, /) para construir la expresión.
3. Presiona el botón `=` para obtener el resultado.
4. Usa el botón `C` para limpiar la pantalla y empezar de nuevo.

## Instalación
1. Clona o descarga este repositorio:
   ```bash
   git clone https://github.com/romagaco/calculadora


## IMPORTANTE: eval() te permite ejecutar un string como si fuera código java script. Es una herramienta interesante de usar pero es una brecha de seguridad. la usamos para practicar js pero no se recomienda su uso bajo ningún caso en código de producción 
