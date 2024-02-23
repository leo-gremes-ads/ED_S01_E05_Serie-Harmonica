<div>
  <img src="https://www.fateczl.edu.br/assets/logos/fatec-zl.png" height=100>
  <img src="https://www.fateczl.edu.br/assets/logos/novo-logo-colorido.png" align="right" height=100>
</div>

<h2 align="center">Análise e Desenvolvimento de Sistemas</h2>
<h3 align="center">Estrutura de Dados</h3>
<h4>Semana 01</h4>

<h4>
  
[Lista 1 - Recursividade](https://github.com/leo-gremes-ads/ED_S01_E01_Soma-Naturais/blob/main/Lista%201%20-%20Recursividade.pdf) - Exercício 5
</h4>
Lista de exercícios para praticar os conceitos de recursividade aprendido em disciplinas dos semestres anteriores juntamente com as explicações e demonstrações realizadas em sala de aula.

Funções recursivas são funções que chamam a si mesmas. Nesta lista, os principais pontos abordados foram o ponto de parada, que é o momento em que a função deve parar de chamar a si mesma e deve começar a retornar valores, e a maneira que devemos utilizar para fazer essas chamadas recursivas, que é a relação da função com as outras execuções dela.

<h4>Resolução</h4>
<p>Nos exercícios que apresentam operações sobre uma série de números, podemos entender que o resultado série toda é igual ao resultado da série do penúltimo valor operado com o último, identificando assim a relação entre as funções.<br>
Ex.: Podemos enxergar que a soma dos 5 primeiros números naturais (0 + 1 + 2 + 3 + 4) é igual ao 5º número mais a soma dos 4 primeiros ( 4 + (0 + 1 + 2 + 3)), identificando assim a relação entre as funções.
<p>Para os pontos de parada, devemos identificar um ponto com valor conhecido onde poderemos definir o retorno da função, fazendo com que ela pare de realizar chamadas. No caso do exemplo acima, a soma de todos os números naturais até o primeiro será igual ao próprio número, fazendo com que esse seja o ponto de parada.
A mesma lógica pode ser adaptada para os exercícios de fatorial e da série harmônica encontrados na lista.

<p>Para os exercícios com vetores, cada chamada da função será equivalente a uma posição do vetor, de traz pra frente, sendo assim, o ponto de parada será a posição 0 do vetor. A relação entre as funções é construída passando o estado atual dos cálculos através de parâmetros, e os utilizando para as operações necessárias.

<p>Nos exercícios, nos foi proposto utilizar um pacote <i>controller</i> onde deveriamos escrever o programa em si e um pacote<i>view</i>, onde deveriamos escrever as interfaces, ou seja, a camada que chama e exibe os resultados do programa.

<h4>Respostas<br><br>

[Exercício 1](https://github.com/leo-gremes-ads/ED_S01_E01_Soma-Naturais)<br>
[Exercício 2](https://github.com/leo-gremes-ads/ED_S01_E02_Menor-Numero-Vetor)<br>
[Exercício 3](https://github.com/leo-gremes-ads/ED_S01_E03_Fatorial)<br>
[Exercício 4](https://github.com/leo-gremes-ads/ED_S01_E04_Negativos-Vetor)<br>
<b>-> Exercício 5</b>
</h4>
