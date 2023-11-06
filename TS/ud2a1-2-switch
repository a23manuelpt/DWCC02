const edad = prompt("Por favor, introduce tu edad: ");
const edadNum = parseInt(edad);

if (!isNaN(edadNum)) {
  switch (true) {
    case edadNum >= 0 && edadNum <= 12:
      console.log("Eres un niño.");
      break;
    case edadNum >= 13 && edadNum <= 18:
      console.log("Eres un adolescente.");
      break;
    case edadNum >= 19 && edadNum <= 30:
      console.log("Eres un joven.");
      break;
    case edadNum >= 31 && edadNum <= 64:
      console.log("Eres un adulto.");
      break;
    case edadNum >= 65 && edadNum <= 100:
      console.log("Eres un jubilado.");
      break;
    default:
      console.log("Edad fuera de los rangos definidos.");
      break;
  }
} else {
  console.log("Por favor, introduce una edad válida.");
}
