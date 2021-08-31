# Homework: Javascript II

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `for`
* `&&`, `||`, `!`

2. Desde la carpeta `Prep` en la carpeta donde clonaste el repo, ingresa el comando `npm test JSII.test.js` para correr los tests automatizados. Al principio, todos los tests estarán fallados/rotos. Encontrarás las funciones para hacer pasar los tests en el archivo `homework.js`.

### Aca tendras acceso a las [Soluciones](https://github.com/atralice/Curso.Prep.Henry/blob/solution/03-JS-II/homework/homework.js)
if (numero% 3 === 0 && numero% 5){
    return "fizzBuzz";
  }
  else if (numero% 3 === 0){
    return "fizz";
  }
else if (numero% 5 === 0){
  return "Buzz";
}
else {
  return numero;
}