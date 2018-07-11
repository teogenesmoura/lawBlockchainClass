# Aula 3

Nessa aula, abordaremos os seguintes tópicos:

- como funciona a blockchain do Bitcoin intuitivamente


Nesta aula, nós faremos uma dinâmica sobre o funcionamento da Blockchain do Bitcoin. Para tanto, usaremos:

 - versões impressas de tweets engraçados (no nosso caso, da conta do Neymar)
 - Barbante
 - Bis 
 - Folhas de papel
 - dados

Passos:

1) Separamos a turma em grupos e afixamos o barbante de um lado a outro da sala. Nele, colocamos a primeira folha, que representa o nó inicial, chamado de 'gênesis';

2) Logo após, distribuímos um conjunto de tweets para cada um dos grupos, que deve escolher qual deles quer colocar na próxima transação, representada por uma folha contendo uma referência para a transação anterior e os dados, que são representados pelos tweets impressos dos grupos.

3) Para cada nova rodada, cada grupo foi dado a oportunidade de sortear um número nos dados. Como a intenção da dinamica era provocar a situação de duas cadeias de blocos se formando, utilizamos apenas um dado. Assim que o grupo de maior pontuação no dado era escolhido, ele ganhava a permissão de persistir uma nova transação na rede, representada por colocar um novo tweet numa folha A4, que continha o tweet e a referência para o bloco anterior. Em troca, o grupo ganhava uma quantidade arbitrária de recompensa (no nosso exemplo, chocolate).

4) Caso dois grupos obtivessem a mesma pontuação no dado, ambos ganhavam o direito de persistir uma transação. No entanto, cada uma ia para um novo fork da cadeia, formando duas cadeias separadas. Para resolver a ambiguidade, na próxima rodada o grupo que tirar o maior valor no dado ganha o direito de escolher qual das duas cadeias persistir como sendo a cadeia de blocos final. Limitamos a quantidade de possíveis colisões a 1, então no caso de um novo empate no maior número tirado nos dados, uma nova rodada era feita para resolver a ambiguidade.

5) No final, os alunos foram capazes de formar uma cadeia de blocos que continham dados (os tweets), fazendo esforço computacional (representado pelos dados), e ganhar uma recompensa por isso (o chocolate). Desse modo, caracterizamos, simplificadamente, o funcionamento de uma rede blockchain didaticamente para alunos sem experiência de programação. 
