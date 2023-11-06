function tablaMultiplicar9() {
  for (let i = 1; i <= 10; i++) {
    console.log(`9 x ${i} = ${9 * i}`);
  }
}

function fibonacci() {
  const fib: number[] = [0, 1];
  for (let i = 2; i < 10; i++) {
    fib[i] = fib[i - 1] + fib[i - 2];
  }
  console.log("Los primeros 10 números de la sucesión de Fibonacci:");
  console.log(fib.join(", "));
}

function esPrimo(numero: number): boolean {
  if (numero <= 1) return false;
  if (numero <= 3) return true;

  if (numero % 2 === 0 || numero % 3 === 0) return false;

  for (let i = 5; i * i <= numero; i += 6) {
    if (numero % i === 0 || numero % (i + 2) === 0) return false;
  }

  return true;
}

function menu() {
  console.log("Selecciona una opción:");
  console.log("1. Mostrar tabla de multiplicar del 9");
  console.log("2. Mostrar los primeros 10 números de la sucesión de Fibonacci");
  console.log("3. Verificar si un número es primo");
  console.log("4. Salir");

  const opcion = prompt("Ingresa el número de la opción deseada: ");

  switch (opcion) {
    case "1":
      tablaMultiplicar9();
      break;
    case "2":
      fibonacci();
      break;
    case "3":
      const num = prompt("Introduce un número para verificar si es primo: ");
      if (esPrimo(Number(num))) {
        console.log(`${num} es un número primo.`);
      } else {
        console.log(`${num} no es un número primo.`);
      }
      break;
    case "4":
      console.log("¡Adiós!");
      break;
    default:
      console.log("Opción no válida. Por favor, selecciona una opción válida.");
      menu();
  }
}

menu();
