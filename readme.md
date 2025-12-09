let idade = 18;
let nome = "joao"


if(idade >= 18) {
    console.log(`${nome} tem ${idade} anos e é maior de idade.`)
} else (
    console.log(`${nome} tem ${idade} anos e é menor de idade!`)
)

2)
let num = 0;

if (num > 0){
    console.log(`o numero é POSITIVO`)
} else if (num < 0) {
    console.log(`o número é NEGATIVO`)
} else {
    console.log(`o numero é ZERO`)
}

3)
let num1 = 33;
let num2 = 33;

if(num1 > num2) {
    console.log(`${num1} é maior que ${num2}`)
} else if (num2 > num1){
    console.log(`${num2} é maior que ${num1}`)
} else {
    console.log(`os numeros sao iguais`)
}

4)
let num = prompt("digite um numero:")

if (num % 2 == 0) {
    console.log(`o numero é par`)
} else {
    console.log(`o numero é impar`)
}

5)

let nota1 = Number(prompt(`digita sua nota`));
let nota2 = Number(prompt(`digita sua nota`));
let nota3 = Number(prompt(`digita sua nota`));
let media = Number(nota1 + nota2 + nota3) / 3;

if(media >= 7) {
    console.log(`nota: ${media.toFixed(2)}`)
    console.log(`Aprovado`)
} else if (media >=5 && media < 7) {
    console.log(`nota: ${media.toFixed(2)}`)
    console.log(`recuperação`)
} else {
    console.log(`nota: ${media.toFixed(2)}`)
    console.log(`reprovado`)
}

6 )
let valor = Number(prompt(`valor da compra:`));

if(valor > 100) {
    let desconto = (valor * 10)/100;
    let valoraPagar = valor - desconto;
    console.log(`seu desconto é de ${desconto}`)
    console.log(`valor a pagar: R$ ${valoraPagar}`)
}

7)
let ano = Number(prompt(`qual o ano:`));

if (ano % 400 === 0) {
    console.log(`é bissexto`)
} else if (ano % 4 === 0 && ano % 100 != 0) {
    console.log(`é bissexto`)
} else {
    console.log(`não é bissexto`)
}

8) 
let user = prompt(`qual login?`)
let senha = Number(prompt(`digite sua senha:`))

if(user === "admin" && senha === 1234) {
    console.log(`acesso permitido`)
} else {
    console.log(`acesso negado`)
}

9)
let valorCompra = Number(prompt(`qual o valor da compra:`))

if(valorCompra >= 200) {
    console.log(`FRETE GRÁTIS`)
} else {
    console.log(`VALOR DO FRETE: R$20,00`)
}

10)
let num = Number(prompt(`digite um numero:`))

if (num > 10 && num < 50) {
    console.log(`esta no intervalor`)
} else {
    console.log(`fora do intervalor`)
}

