<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exercícios JavaScript</title>
</head>
<body>

  <script src="exercicios.js"></script>

</body>
</html>

console.log("Exercício 1:");
let contador1 = 1;
while (contador1 <= 50) {
  console.log(contador1);
  contador1++;
}


console.log("\nExercício 2:");
let contador2 = 10;
do {
  console.log(contador2);
  contador2--;
} while (contador2 >= 0);


console.log("\nExercício 3:");
for (let i = 1; i <= 100; i++) {
  if (i % 2 === 0) {
    console.log(i);
  }
}
