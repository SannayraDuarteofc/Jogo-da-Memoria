# Jogo da Memória Matemático

## Objetivo do Projeto

O Jogo da Memória Matemático é um projeto educacional desenvolvido em 2025 enquanto trabalhava como professora de reforço particular com o objetivo de auxiliar o ensino das quatro operações matemáticas e estimular o raciocínio lógico de crianças atípicas de forma lúdica e interativa.

A proposta surgiu da busca por uma maneira mais divertida e envolvente de aprender matemática, e principalmente, de aprender quais operações geram resultados semelhantes, unindo o forte impacto e adesão das crianlas à tecnologia, principalmente aos jogos, com a dinâmica de um jogo da memória, para transformar exercícios matemáticos em uma atividade prática e divertida.

O jogo cumpriu seu objetivo educacional, contribuindo para uma melhora significativa no desempenho escolar das crianças e ajudando a tornar o aprendizado da matemática mais interessante e divertido.

Atualmente, o projeto está passando por atualizações no layout, com o objetivo de aprimorar sua apresentação visual e a experiência de uso.

## Como funciona

O jogo apresenta cartas com operações matemáticas. O jogador deve encontrar pares de cartas cujos resultados sejam iguais, exercitando a memória, a atenção, o cálculo mental e o raciocínio lógico.

O projeto possui três fases, com diferentes níveis de abordagem das operações matemáticas. Cada fase oferece uma oportunidade de praticar os cálculos por meio da associação entre expressões matemáticas equivalentes. 

## Fases do jogo

### Fase 1 — Soma, subtração e multiplicação

A primeira fase trabalha as operações de adição, subtração e multiplicação. O jogador deve relacionar operações diferentes que apresentam o mesmo resultado, como `4 + 4` e `2 x 4`.

Essa etapa busca desenvolver o cálculo mental e reforçar a compreensão das operações básicas por meio da associação de resultados.

### Fase 2 — As quatro operações

A segunda fase amplia o conteúdo ao incluir a divisão, além da adição, subtração e multiplicação.

O jogador precisa identificar pares de operações equivalentes, como `10 : 2` e `3 + 2`, exercitando diferentes formas de chegar ao mesmo resultado.

### Fase 3 — Prática das quatro operações

A terceira fase mantém o trabalho com as quatro operações matemáticas, mas com uma dificuldade maior, utilizando mais de uma operação por carta, permitindo a evolução na identificação de resultados equivalentes e no raciocínio lógico,

Assim como nas fases anteriores, o objetivo é encontrar os pares corretos, estimulando a memória e a consolidação dos conhecimentos matemáticos.

> Os valores contidos no código são apenas exemplos, com objetivo de apresentar o jogo, e foram mudados ao decorrer das aulas

## Estrutura do código

### HTML

O HTML define a estrutura das páginas do jogo. A página inicial apresenta o título e os botões de acesso às três fases. Cada fase possui suas próprias cartas, título e controles para reiniciar a partida ou retornar ao início.

### CSS

São utilizadas media queries para adaptar o layout a diferentes tamanhos de tela. O projeto está passando por atualizações nessa parte para aprimorar a experiência visual.

### JavaScript

**Funções:**

- `flipCard()` permite virar as cartas, respeitando o limite de duas cartas por tentativa e impedindo que cartas já combinadas sejam selecionadas novamente.

- `checkMatch()` compara os resultados das duas cartas selecionadas. Se os valores forem iguais, o par é considerado encontrado. Caso contrário, as cartas voltam à posição inicial após um breve intervalo.

- `evaluateCard()` interpreta as expressões matemáticas das cartas, substituindo os símbolos de multiplicação e divisão pelos operadores correspondentes antes de calcular seus resultados.

- `reiniciarJogo()` reinicia a partida, desvira as cartas e limpa os registros dos pares encontrados.

- `shuffle()` embaralha a ordem das cartas para variar a disposição a cada reinício.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript

## Objetivos educacionais

O projeto busca tornar o aprendizado da matemática mais acessível, interativo e motivador, trabalhando habilidades como:

- Prática das quatro operações matemáticas.
- Desenvolvimento do raciocínio lógico.
- Estímulo à memória e à atenção.
- Associação entre expressões matemáticas e resultados.
- Aprendizado por meio de atividades lúdicas.

## Status do projeto

Desenvolvido em 2025 e atualmente em atualização de layout. O jogo já foi utilizado com finalidade educacional e apresentou resultados positivos no desempenho e no interesse das crianças pela matemática.

## Aprendizados

O desenvolvimento deste projeto proporcionou experiência prática com HTML, CSS e JavaScript, além de demonstrar como a tecnologia pode ser utilizada para criar recursos educacionais que tornam o aprendizado mais envolvente.

Mais do que desenvolver um jogo, o projeto buscou transformar o ensino da matemática em uma experiência divertida e contribuir para a aprendizagem das crianças.
