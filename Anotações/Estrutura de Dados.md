# Estrutura de dados

É uma estrutura organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados de forma correta.
Essas estruturas encontram muitas aplicações no desenvolvimento de sistemas, sendo que algumas são altamente especializadas e utilizadas em tarefas específicas.
Usando as estruturas adequadas através de algoritmos, podemos trabalhar com uma grande quantidade de dados, como aplicações em bancos de daods ou serviços de busca.

## Algoritmo

É um conjunto de instruções estruturadas e ordenadas, seu objetivo é realizar uma tarefa ou operação específica.
Os algoritmos são utilizados para manipular dados nas estruturas de várias formas, como por exemplo: inserir, excluir, procurar e ordenar dados.

Em uma estrutura de dados devemos saber como realizar um determinado conjunto de operações básicas, como por exemplo:
- Inserir dados
- Excluir dados
- Localizar um elemento
- Percorrer todos os itens constituintes da estrutura para visualização
- Classificar, que se resume em colocar os itens de dados em uma determinada ordem ( numérica, alfabética, etc.)

## Principais estruturas de dados

- Vetores
- Registro
- Lista
- Pilha
- Fila
- Árvore
- Tabela Hash
- Grafos

## Vetores e Matrizes

São estruturas de dados simples que podem auxiliar quando há muitas variáveis do mesmo tipo em um algoritmo.

***Vetor ou array unidimensional*** é uma variável que armazena várias variáveis do mesmo tipo.
O ***vetor*** é uma estrutura de dados indexada, que pode armazenar uma determinada quantidade de valores do mesmo tipo.

***Matriz ou array multidimensional*** é um vetor de vetores.
Uma matriz é um vetor que possui duas ou mais dimensões.

## Registros

É uma estrutura que fornece um formato especializados para armazenar informações em memória
Enquanto arrays nos permitem armazenar vários dados de um único tipo de dados, o recurso de Registro nos permite armazenar mais de um tipo de dado.
É composto por campos que especificam cada uma das informações que o compõem.
Toda estrutura de registro tem um nome (ex: livro), e seus campos podem ser acessados por meio do uso do operador ponto (.), por exemplo, para acessar o preço de um livro, poderíamos utilizar a seguinte declaração:

*livro.preço*

## Listas

Estrutura de Dados tipo Lista, armazena dados de um determinado tipo, em uma ordem específica
A diferença entre ***listas e arrays (vetores e matrizes)*** é que as listas possuem tamanho ajustável, enquanto arrays possuem tamanho fixo

Existem dois tipos de listas:

***- Ligadas:*** existem os nós onde cada um dos nós conhece o valor que está sendo armazenado em seu interior além de conhecer o elemento posterior a ele: por isso ela é chamada de “lista ligada”, pois os nós são amarrados com essa indicação de qual é o próximo nó.

***- Duplamente Ligadas:*** Constituem uma variação das listas ligadas.

A grande diferença das listas duplamente ligadas para as listas ligadas, é que elas são bidirecionais. 
Vimos que, naturalmente, não conseguimos “andar para trás” em listas ligadas, pois os nós de uma lista ligada sabem somente quem é o próximo elemento. 
Nas listas duplamente ligadas, os nós sabem quem é o próximo elemento e também quem é o elemento anterior, o que permite a navegação reversa.

## Pilhas 

É uma estrutura de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenado.
O acesso aos itens de uma pilha é restrito - somente um item pode ser lido ou removido por vez.

Existem dois tipos de pilhas:

***- LIFO ou UEPS:*** A estrutura do tipo pilha LIFO (Last in First Out) ou UEPS (Último que Entra Primeiro que Sai), apresenta o seguinte cenário: o primeiro elemento a ser retirado é o último que tiver sido inserido

***- FIFO ou PEPS:*** A estrutura do tipo pilha FIFO (First in First Out) ou PEPS (Primeiro que Entra Primeiro que Sai), apresenta o seguinte critério: o primeiro elemento a ser retirado é o primeiro que tiver sido inserido.

## Filas

Admite remoção de elementos e inserção de novos sujeita à seguinte regra de operação:
O elemento removido é o que está na estrutura há mais tempo, ou seja, o primeiro objeto inserido na fila é também o primeiro a ser removido seguindo o conceito FIFO.

## Árvore

É uma estrutura que organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da árvore, chamado de raiz e existem os elementos subordinados a ele, que são chamados de nós ou folhas.

## Tabela Hashing

É uma generalização da idéia de array, porém utiliza uma função denominada Hashing para espalhar os elementos, fazendo com que os mesmos fiquem de forma não ordenada dentro do “array” que define a tabela.
Permite a associação de “valores” a “chaves” 

***valores:*** é a posição ou índice onde o elemento se encontra
***chave:*** parte da informação que compõe o elemento a ser manipulado

Espalhar facilita a busca na estrutura de dados, pois a partir de uma chave podemos acessar de forma rápida uma posição do “array”

## Grafos

São estruturas que permitem programar a relação entre objetos

***Objetos:*** São vértices ou “nós” do garfo
Os relacionamentos são arestas
