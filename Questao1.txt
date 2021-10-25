//  Questão 1
// Problema FizzBuzz:
// Escreva um método Java que imprime os números de 1 a 50.
// Mas para múltiplos de três escreva "Fizz" ao invés do número
// e para múltiplos de cinco escreva "Buzz".
// Para números múltiplos de três e cinco imprima "FizzBuzz".

for (let i = 1; i <= 50; i++) {
  if (i % 3 == 0 && i % 5 == 0) {
    console.log(" FizzBuzz");
  } else if (i % 5 == 0) {
    console.log(" Buzz");
  } else if (i % 3 == 0) {
    console.log(" Fizz");
  } else {
    console.log(i);
  }
}