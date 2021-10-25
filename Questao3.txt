// Implementar uma interface de entrada, com dois campos ambos numéricos, aceitando valores de 1 a 5.
// No primeiro, se o valor for igual a 3,4 ou 5 deve sinalizar "Correto".
// No segundo, se o valor for menor que o primeiro deve sinalizar "Correto".
// Criar um botão/ação, que ao ser disparado, sinaliza a soma dos dois valores.

function dados() {
  a = prompt("Digite um número de 1 a 5: ");

  while (a > 5) {
    a = prompt("Número maior que 5, por favor digitar um número de 1 a 5: ");
  }

  if (a == 3 || a == 4 || a == 5) {
    console.log("Correto");
  }

  b = prompt("Digite outro número de 1 a 5: ");

  while (b > 5) {
    b = prompt("Número maior que 5, por favor digitar um número de 1 a 5: ");
  }

  if (b < a) {
    console.log("Correto");
  }

  soma = prompt(
    "Deseja efetuar a soma dos dois valores? Se desejar digite S para sim e N caso não:"
  );

  conf = soma;

  if (conf === "S" || conf === "s") {
    soma = Number(a) + Number(b);
    console.log(soma);
  } else {
    console.log("Programa encerrado pelo usuário.");
  }
}

console.log(dados());