# Number in the Range

Función que indica si un número está dentro del rango de otro número devolviendo un valor booleano:
* Si el segundo número es menor al primero = true
* Si el segundo número es mayor al primero = false

## Instalación

1. Instala la dependencia dentro de la carpeta de tu proyecto
```bash
$ npm install numberintherange
```
2. Importa el paquete a tu proyecto
```javascript
const numberInTheRange = require('numberintherange');
```

## Sintaxis
```javascript
numberRange(number1, number2)
```
number1 = numero que define el rango de 0 a n
number2 = numero para comparar

## Ejemplos

```javascript
const numberInTheRange = require('numberintherange');

if(numberInTheRange.numberRange(5,1)) {
  console.log('El número se encuentra en el rango');
} else {
  console.log('El número excede el límite permitido');
}
```

```javascript
const { numberRange } = require('numberintherange');

if(numberRange(5,1)) {
  console.log('El número se encuentra en el rango');
} else {
  console.log('El número excede el límite permitido');
}
```
