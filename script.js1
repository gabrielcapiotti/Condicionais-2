/*
Escreva um algoritmo que armazene o número total de eleitores de
um município, o número de votos brancos, nulos e válidos. Calcular
e escrever o percentual que cada um representa em relação ao
total de eleitores. O algoritmo deve fazer uma validação para que as
porcentagens dos votos armazenados (brancos, nulos e válidos)
respeitem o limite do número total de eleitores, ou seja, garantir que
a soma dos votos brancos, nulos e válidos não seja maior que o
número total de eleitores.
*/

// Solicita o número total de eleitores
let totalEleitores = parseInt(prompt("Digite o número total de eleitores:"));

// Solicita o número de votos brancos
let votosBrancos = parseInt(prompt("Digite o número de votos brancos:"));

// Solicita o número de votos nulos
let votosNulos = parseInt(prompt("Digite o número de votos nulos:"));

// Solicita o número de votos válidos
let votosValidos = parseInt(prompt("Digite o número de votos válidos:"));

// Validação para garantir que a soma dos votos não ultrapasse o número total de eleitores
if (votosBrancos + votosNulos + votosValidos > totalEleitores) {
    console.log("Erro: A soma dos votos não pode ser maior que o número total de eleitores.");
} else {
    // Calcula os percentuais de votos brancos, nulos e válidos
    let percentualBrancos = (votosBrancos / totalEleitores) * 100;
    let percentualNulos = (votosNulos / totalEleitores) * 100;
    let percentualValidos = (votosValidos / totalEleitores) * 100;

    // Exibe os resultados
    console.log(`Percentual de votos brancos: ${percentualBrancos.toFixed(2)}%`);
    console.log(`Percentual de votos nulos: ${percentualNulos.toFixed(2)}%`);
    console.log(`Percentual de votos válidos: ${percentualValidos.toFixed(2)}%`);
}

