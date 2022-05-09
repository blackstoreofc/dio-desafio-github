# Portugol

É uma pseudo linguagem que permite ao leitor desenvolver algoritmos estruturados em portugues de forma simples e intuitiva, independentemente de linguagem de programação
É uma pseudo linguagem que permite ao programador pensar no problema em si e não no equipamento que irá executar o algoritmo

## Desvios condicionais

***Se:*** é utilizada a palavra reservada se, a condição a ser testada entre parenteses e as instruções que devem ser executadas entre chaves caso o desvio seja verdadeiro. 
ex: 

se (media>=7) {
          escreva("Parabéns!! Você foi aprovado!!”)
}

***se-senao:*** utilizada quando a condição for falsa

se (media>=7) {
          escreva("Parabéns!! Você foi aprovado!!”)
}

senao {
          escreva(“Infelizmente você foi reprovado")
}

***caso:*** esse comando é similar aos comandos se e senao, e reduz a complexidade na escolha de diversas opções.
Apesar de suas similaridades com o se, ele possui algumas diferenças. Neste comando não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos.

## Laços de repetição

É uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um contador. 

ex: 

funcao inicio()
{
          inteiro contador, limite, resultado
          contador = 0
          limite = 10
          faca
          {
                  resultado = 9 * contador
                  escreva (“9 x + contador + “=” + resultado + “\n”)
                  contador ++
           } enquanto (contador <= limite)
}

## Matriz e Vetores

Matriz é uma coleção de variáveis de mesmo tipo, acessíveis com um único nome e armazenados contiguamente na memória
A individualização de cada variável de um vetor é feita através do uso de índices.
Os Vetores são matrizes de uma só dimensão.

ex:

cadeia Vetor[5];   // declara um vetor de 5 posições 
cadeia Matriz[5][3];  // declara uma matriz de 5 linhas e 3 colunas

cadeia frutas[4];
frutas[0]=”Maçã”
frutas[1]=”Pera”
frutas[2]=”Uva”
frutas[3]=”Melão

escreva (frutas[2])

cadeia cesta[][] = {{“Maçã”,”100”},{“Pera”,”200”},{“Melão”,”300”}}

escreva (“Fruta: “ + cesta[0][0] + Quantidade: “ + cesta[0][1])
