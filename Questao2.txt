// Implemente um método para percorrer um array, verificando se o número é par.
// Se for verdadeiro, multiplicar por dois, e se algum for maior que 50 retornar verdadeiro.
// Criar outro método seguindo os mesmos requisitos, porém para números ímpares, e o valor de teste para verdadeiro é 40.

//PAR

let array = [];

for (let i = 1; i <= 100; i++) {
  array.push(i);
}

for (let i = 1; i < array.length; i++) {
  if (array[i] % 2 === 0) {
    array[i] = array[i] * 2;

    if (array[i] > 50) {
      array[i] = "True";
    }
  }

  console.log(array[i]);
}

//IMPAR

// let array = [];

// for (let i = 1; i <= 100; i++) {
//   array.push(i);
// }

// for (let i = 1; i < array.length; i++) {
//   if (array[i] % 2 === 1) {
//     array[i] = array[i] * 2;

//     if (array[i] > 40) {
//       array[i] = "True";
//     }
//   }
//   console.log(array[i]);
// }
