# SUPER TRUNFO


No Trabalho Final de Linguagem de Programação Orientada a Objetos II em 2018/2, vamos fazer uma versão digital para o jogo Super Trunfo. O Super Trunfo é um jogo de cartas, relativamente simples e bastante popular. Hoje em dia, existem algumas variações, mas a ideia é trabalharmos com as regras básicas, mudando apenas o tema.

Tradicionalmente, estão em disputa 32 cartas, divididas em oito grupos de quatro cartas (1A-1D, 2A2D,… 8A-8D), sendo que uma delas é a carta "Super Trunfo", que ao entrar em disputa, pode ser invocada para tomar as outras cartas na mão dos oponentes.

O jogo possui variações, em torno de diversos temas, entre eles:

Animais (Cães, Gatos, Dinossauros, Tubarões, Aranhas, Escorpiões, etc);
Aviões (de caça, à Jato...);
Carros (de Rally, de Luxo, de Marcas Famosas - GM, Ford, Volkswagen, Fiat);
Países;
Times brasileiros (Internacional, Grêmio, Palmeiras, Santos, Flamengo, Vasco e outros);
Além de outros temas específicos como: NBA, Cavaleiros do Zodíaco e super-heróis da Marvel.
O jogo: baseia-se na comparação dos valores de sua carta com a dos outros jogadores. Para sua carta vencer, a característica escolhida precisa ter valor maior ou menor (em alguns casos) do que a carta dos seus adversários.

Objetivo:
Ficar com todas as cartas do baralho.

Preparação:
As cartas são distribuídas em número igual para cada um dos jogadores.
Cada jogador forma seu monte e só vê a primeira carta da pilha.
As cartas possuem informações: força, peso, potência, velocidade e comprimento, dependendo do tema escolhido.
É com estas informações que cada um vai jogar.

Como jogar:
Se você é o primeiro a jogar, escolha, entre as informações contidas em sua primeira carta, aquela que você julga ter o valor capaz de superar o valor da mesma informação que se encontra na carta que seus adversários têm em mãos. Por exemplo: você escolhe a informação velocidade, menciona-a e abaixa a carta na mesa. Imediatamente todos os outros jogadores abaixam a primeira carta de suas pilhas e conferem o valor da informação. Quem tiver o valor mais alto ganha as cartas da mesa.
O próximo jogador será o que venceu a rodada anterior. Assim prossegue o jogo até que um dos participantes fique com todas as cartas do baralho, vencendo a partida.
Se dois ou mais jogadores abaixam cartas com o mesmo valor máximo, os demais participantes deixam suas cartas na mesa e a vitória é decidida entre os que empataram. Para isso, quem escolheu inicialmente diz um novo item de sua próxima carta, ganhando as cartas da rodada quem tiver o valor mais alto.
Existe, entre as cartas, uma carta SUPER TRUNFO. Esta carta vence todas as cartas do baralho, independentemente do valor de suas características. Ela perde apenas para as cartas que tenham a letra A (1A, 2A, 3A, etc), marcada na parte superior de cada uma.
O participante cuja carta da rodada for a marcada como "Super Trunfo" automaticamente ganha a rodada, a não ser que a carta de um dos participantes seja letra A (1A, 2A, 3A, etc) quando este ganha a rodada e, consequentemente, a carta "Super Trunfo".
Quando a carta SUPER TRUNFO aparecer, a comparação será automática com as cartas dos adversários, sem necessidade de você escolher uma característica de sua carta.
O jogo termina quando um dos jogadores ganhar todas as cartas do baralho. Abstrações (para fins de implementação):
Cada equipe deve escolher o tema do seu jogo. O tema escolhido será a classe abstrata e, a partir dessa, serão definidas as subclasses.
O jogo ocorrerá entre dois jogadores, devendo ter dois montes, distribuídos a partir das cartas embaralhadas.
A cada jogada, o jogador vira a carta de cima do seu monte, exibindo-a e indica qual característica deve ser considerada na disputa.
Considerações importantes (LEIA com atenção):
O programa deve ser desenvolvido em Linguagem de Programação Java, com recursos de orientação a objetos.
Os trabalhos podem ser feitos em equipes (duplas ou trios) ou individualmente.
Os arquivos que compõem o projeto (classes e teste/aplicação) devem ser compactados e postados no Moodle.
O arquivo compactado deve ter o nome e sobrenome dos alunos. Exemplo: joaoSilvaEPedroBarcelos.zip.
A implementação deve usar obrigatoriamente classes, objetos, coleções (Array ou ArrayList) e herança.
Data de entrega para todos os trabalhos no Moodle: 20/11/2018 (impreterivelmente, não haverá adiamentos). As apresentações ocorrerão durante o horário da aula no dia 20/11, por sorteio.
Trabalhos iguais, notas iguais: ZERO.
Só serão aceitos programas sem erro de compilação.
Não serão aceitos trabalhos fora do prazo.
A nota do trabalho depende da apresentação individual do aluno.
Trabalhos, mesmo que postados no Moodle, mas não apresentados, não serão considerados.
Os alunos podem receber notas diferentes.
Se o aluno não dominar o programa, ou seja, não conseguir explicá-lo convincentemente; isso pode ser encarado como cópia e o programa poderá ser desconsiderado.
Critérios de Avaliação quanto à implementação:
Escolha do tema e correta definição das respectivas classes (classe abstrata, superclasse e subclasses - uso de herança)
Criação do baralho completo (uso de coleções)
Atualização do monte de cada jogador, a cada ciclo de execução
Solicitação de indicação da característica na carta jogada
Percepção de quem ganhou
Percepção de situação de empate
Repetição da solicitação para a nova carta
Percepção de final do jogo corretamente
Uso correto dos conceitos de orientação a objetos (classes, objetos, coleções, encapsulamento, herança e polimorfismo)
Documentação do sistema, através do seu diagrama de classes.
