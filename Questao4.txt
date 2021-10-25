//Considerando as seguines entradas: produto (dois caracteres), marca (um caracter), valor (inteiro).
//Implementar um método que retorne verdadeiro ou falso seguindo as seguintes regras:
//Se o valor for menor que 5, a marca não for "A", "B" ou "C" e produto igual a "AB" ou "BA", rejeitar.
//Se o produto for composto de dois digitos iguais e valor entre 10 e 30, rejeitar.
//Se a marca for "A" rejeitar.
//Se valor acima de 50, deve rejeitar.
//Outros casos devem ser aceitos.



if(valor>5 && marca === "A" || marca === "B" || marca === "C" && produto === "AB" || produto === "BA"){
    console.log("Produto Rejeitado")
}

if(produto[0] === produto[1] && valor <= 30 && valor >= 10){
    console.log("Produto Rejeitado")
}

if(marca === "A"){
    console.log("Produto Rejeitado")
}

if(valor > 50){
    console.log("Produto Rejeitado")
}

console.log("Produto Aceito"("xx", "x", ))