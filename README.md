TaeMOBA
=======

O TaeMOBA (nome provisório) será um jogo competitivo online desenvolvido por
[Taelin](https://github.com/VictorTaelin) em seu tempo livre da
[HOC](https://HigherOrderCO.com).

## Resumo

O TaeMOBA nasce de uma frustração pessoal com o game design MOBAs mobernos. Na
minha percepção, sinto que poucos devs pensam fora da caixa. Dogmas raramente
são questionados e mecânicas novas raramente "saem da caixa". De forma curta,
todos os MOBAs mobernos são extremamentes parecidos uns com os outros. O TaeMOBA
propõe-se a quebrar completamente a fórmula, criando algo completamente novo e
original, baseado em ideias e pensamentos que acumulei ao longo de anos.

Uma das características mais importantes desse projeto é que seu design não será
pré-definido em um GDD estático, como é feito geralmente. Ao invés disso,
diversas ideias serão exploradas, selecionadas e descartadas, permitindo com que
o resultado final seja lapidado de forma interativa e evolutiva. Ou seja, o
TaeMOBA, nos seus primeiros meses, terá um **Game Design dinâmico** que aos
poucos será solidificado.

Isso é possível porque o jogo será programado usando uma linguagem de
programação exclusiva e altamente abstrata, conhecida como "Cálculo das
Construções", implementado [neste](https://github.com/VictorTaelin) repositório.
Essa escolha permitirá com que o código evolua de forma extremamente veloz, e
que mudanças drásticas sejam feitas em pouco tempo, permitindo com que
exploremos diversos conceitos antes de chegar ao design final. Essa escolha
também nos permite trocar de game engine como facilidade, nos livrando de
depender ou ficar preso a um framework específico.

## Conceitos

Apesar do design do TaeMOBA ainda estar sendo definido, já temos diversos
conceitos em potencial. Usaremos o espaço para descrever todos eles, cobrindo
tópicos que vão desde a economia e o marketing do jogo, até conceitos de game
design e da arte. Quando não especificado, deve-se assumir que TaeMOBA será
parecido com outros jogos do gênero. Por exemplo, o conceito de um client, a
ideia de "partidas 5v5 com um vencedor", os modos de jogo (normal, rankeado),
elos, lobbies, friend lists, cosméticos, chats; tudo isso será herdado de MOBAs
tradicionais sem grandes mudanças. Porém, no jogo em si, muitas coisas serão
alteradas significativamente, e, nesse espaço, descreverei algumas delas. Não
necessariamente tudo que está aqui será adotado, mas fazem parte do conceito
inicial. Essa não é uma lista exaustiva, e será atualizada conforme eu tiver
tempo de formalizar minhas ideias. 

### Marketplace de Cosméticos

Em 2021, o jogo Fortnite gerou uma receita de quase **6 bilhões** de dólares
apenas com a venda de cosméticos digitais
([fonte](https://www.tweaktown.com/news/91786/fortnite-made-nearly-6-billion-from-in-game-purchases-2021/index.html#:~:text=According%20to%20data%20compiled%20by,game%20digital%20cosmetics%20throughout%202021.)).
Ao mesmo tempo, designers e artistas brasileiros vendem seus trabalhos - que,
muitas vezes, levam dias para criar - por valores tão baixos quanto R$100, ou
até menos. Ou seja, jogos online criaram um mercado gigantesco onde pessoas
gastam fortunas comprando artes online; afinal, o que mais seria uma "skin"?;
porém, esse valor é integralmente capturado por grandes empresas, e artistas
da vida mal se beneficiaram com ele! É hora de bagunçar esse mercado.

O TaeMOBA vem para a fazer, com as grandes empresas de GameDev, o que o Uber fez
com os Taxis: trazer esse valor de volta para aquele que o produz. No TaeMOBA,
haverá um mercado de cosméticos onde artistas poderão criar e enviar suas
próprias skins, e uma grande parte da receita gerada por essas skins será
enviada diretamente para o artista.

### Revshare com Pro Players (aka "ELO Remunerado")

Grande parte do sucesso de jogos como League of Legends e Valorant pode ser
atribuído ao seu cenário competitivo. Em 2018, a Riot ofereceu um Prize Pool de
6 milhões de dólares para os campeões do campeonato mundial de League of
Legends. Parece um valor exorbitante, porém, essa percepção logo se desvanece
ao percebermos que isso é cerca de 0.1% da receita de cosméticos (que é uma
fração da receita total). Ademais, a base do cenário competitivo - isso é,
jogadores que dão corpo e alma para alcançar os elos mais altos dos modos
rankeados - é completamente não remunerada, o que cria incertezas, inseguranças, 
falta de estabilidade econômica para aqueles que são a base destes eventos que
geram, direta e indiretamente, rios de lucros para as empresas.

O TaeMOBA pretende quebrar esse paradigma e valorizar o cenário competitivo de
verdade, redirecionando uma % fixa da receita total diretamente para os
jogadores de elo mais alto dos modos rankeados, também conhecidos como
"Challengers". Isso não somente dá uma margem de segurança e estabilidade para
aqueles que pretendem, um dia, fazer parte do modo competitivo, como aumenta o
próprio valor do modo rankeado.

### Mecânicas Únicas ("Abathurização")

Um dos MOBAs mais divertidos que eu joguei, Heroes of The Storm, se destacou
pela criação de personagens com mecânicas únicas, que quebravam a fórmula dos
MOBAs tradicionais de maneiras totalmente inovadoras. Por exemplo, "Abathur" é
um personagem extremamente frágil, que facilmente morre com um único ataque;
porém, ele possui uma habilidade capaz de escolher e buffar qualquer personagem
do jogo, com alcance global. Dessa forma, a experiência de jogar com esse
personagem é uma experiência totalmente diferente; um jogador de Abathur
raramente move seu personagem, passando maior parte do tempo olhando para o
mapa, de forma global, buscando oportunidades para influenciar positivamente seu
time. Outros personagens que quebram as regras incluem Cho'Gall (um único boneco
controlado por dois jogadores), o Murky (que não "morre"; ao invés disso, nasce
quase imediatamente no seu ovo), e o Deathwing (um dragão gigante que é
totalmente imune a controle de grupo e pode voar pelo mapa, como um raid boss). 

No TaeMOBA, esse princípio será adotado e amplificado significativamente. Ou
seja, teremos personagens que quebram completamente a fórmula padrão, de formas
que nem mesmo o HotS se atreveu a quebrar. Alguns exemplos:

A. Um fantasma sem "boneco", que atua como um "mestre das torres", afetando as
estruturas e os minions aliados, de modo a auxiliar seu time na vitória.

B. Uma "planta alien invasiva", que, ao contrário, tem dezenas de "bonecos",
porém imóveis, sendo seu objetivo se espalhar pelo mapa, formando uma "floresta"
que favorece seu time em pontos chave.

C. Um "mercador", que substitui a loja e passa o jogo inteiro forjando itens
para os seus aliados.

D. Uma "tartaruga encouraçada", que se move a 30% da velocidade, porém possui
uma quantidade de vida e defesa extraordinária.

E. Uma "monge psíquico" (pense no Abra) que não possui qualquer habilidade de
dano, porém pode se teletransportar pelo mapa, e transportar aliados pelo mapa.

Esses e outros personagens que "driblam das regras" serão constantemente
explorados e testados no TaeMOBA. Em outros MOBAs, conceitos assim são raramente
adotados, e o boneco, em geral, tem basicamente os mesmos atributos, a mesma
move speed, as mesmas funções (jungler, ADC, etc.). Isso é feito pois esses
MOBAs não foram projetados pensando em personagens muito diferentes e, portanto,
a presença deles poderia causar problemas e frustrações. Por exemplo, é
desprazeroso ter que mudar a forma de jogar, só porque alguém escolheu um
personagem "rule-bending". E balancear personagens fora da regra é desafiador.

Eu acredito que esses e outros problemas, quando ocorrem, são causados por uma
falha de game design, e que existem diversas formas competentes de projetar os
personagens, e de adaptar o próprio jogo, de forma a evitar os pontos negativos,
abrindo espaço para a criação de personagens que fogem da regra e proporcionam
uma experiência totalmente única. Por exemplo, cada personagem que "dobra as
regras" deve ter uma fraqueza clara e explorável que anule sua mecânica, dando
uma opção de resposta para o time adversário. E um sistema de draft inteligente
onde seja possível escolher o tipo de aliado que você aceita ter no seu time
significativamente reduziria a frustração de estar com um boneco que te força a
mudar sua forma de jogar.

### Scaling Anti-Snowball (-nível -gold -toxicidade -tecladosquebrados)

Uma das características mais frustrantes de MOBAs é o "efeito bola-de-neve", ou
seja, quando "uma vitória torna a próxima vitória mais provável". Por exemplo,
imagine que, no primeiro minuto de jogo, você tenha jogado mal, e morra. Você
respira fundo, volta para a lane e começa a jogar muito melhor que o seu
adversário. Porém, em uma luta equilibrado, você deixa seu oponente com 1 HP e
morre. Essa morte foi devido ao efeito bola-de-neve: apesar de ter jogado
melhor, você perdeu essa luta, por conta de coisas que aconteceram no passado.
E, para piorar, na próxima luta, seu oponente estará ainda mais forte!

Se a intenção de um MOBA é ser um esporte digital, então, o efeito bola-de-neve
é uma falha de game design, pois ele cria uma "curva de importância", onde os
primeiros minutos são mais valiosos que os últimos, o que é extremamente
frustrante para o jogador, e um dos maiores geradores de toxicidade. Afinal, se,
aos 5 minutos de jogo, seu time morreu 5 vezes... não importa se vocês jogarem
melhor que o adversário nos últimos 25 minutos, vocês provavelmente vão perder.
Sendo assim, há pouco incentivo para abrir o chat e motivar o time. Acaba
ficando mais fácil só xingar todo mundo e desistir aos 15. De fato, a própria
mecânica de desistência é uma consequência do snowball. Não somente, o LoL
implementa uma quantidade obscena de mecânicas para amenizar esse efeito e
tornar o jogo minimamente palatável. Porém, essas medidas apenas jogam a poeira
pra debaixo do tapete, e não atacam a raiz do problema.

Para piorar, esse problemão é algo totalmente artificial, que os próprios devs
do jogo criaram, por não refletirem sobre os efeitos e as consequências das suas
próprias decisões de game design. Veja bem: ao longo toda história dos esportes,
o efeito bola-de-neve jamais foi um problema. Quando você faz uma cesta no
basquete, sua perna não cresce. Quando você faz um gol no futebol, o gol
adversário não fica maior. No futebol, se você joga mal nos primeiros 10
minutos, toma 3 gols, respira fundo e passa a jogar muito melhor que o seu
adversário... você provavelmente vai vencer a partida! Afinal, os 80 minutos que
seguem valem tanto, e os jogadores do time adversário não viraram titãs
colossais por conta daqueles 3 gols iniciais.

o TaeMOBA pretende colocar o efeito snowball em cheque, não através de uma série
de gambiarras e band-aids, mas através de uma decisão muito mais simples: a
remoção, quase completa, de efeitos de "scaling". Ou seja, conceitos como
*nível* e *gold*, que tornam o seu boneco mais forte *numericamente*, serão,
quase totalmente, excluídos do jogo. Em outras palavras, o TaeMOBA pretende
manter a seguinte invariante: **se, a qualquer tempo T do jogo, a equipe X e Y
se enfrentarem, sairá vitoriosa, daquele confronto, aquela que jogar melhorn
essa ocasião, independente do que aconteceu no passado**.

Isso, para alguns, pode levantar alguns questionamentos e preocupações. Por
exemplo, pode-se argumentar que a remoção de níveis necessariamente tornará o
jogo menos competitivo. Esse pensamento está equivocado, e provavelmente ocorre
quando alguém pensa em como seria remover os níveis de um MOBA que ela conheça,
como o LoL. Nesse caso, sim, obviamente o LoL, não alterando nada mais, se
tornaria menos competitivo sem níveis. Porém esse pensamento esquece, ou
subestima, o fato de que o TaeMOBA é um novo jogo, e que é totalmente possível
projetá-lo de modo a manter o mesmo, ou maior, nível de competitividade e skill
ceiling, mesmo sem níveis. Um exemplo simples disso é o jogo Smash Bros, que tem
uma das comunidades competitivas mais antigas e bem-sucedidas, e que não possui
qualquer conceito de nível, stat-checks ou efeito bola-de-neve.

Em resumo, o TaeMOBA pretende ser um esporte digital que elimina o efeito
bola-de-neve de forma bem fundamental, removendo conceitos como "nível" e
"gold", porém mantendo a competitividade de outras formas que não envolvem
"stat-checks". Minha hipótese é que isso não somente diminuirá consideravelmente
a toxicidade do jogo, como tornará ele bem mais divertido, pois todos os minutos
da partida terão o mesmo peso, e comebacks acontecerão naturalmente sempre que
você jogar melhor que o seu adversário na segunda metade do jogo.

### Gráfico

Os gráficos do TaeMOBA ainda não estão completamente definidos. Porém, por conta
do Marketplace de Cosméticos, a intenção é que ele tenha uma câmera top-down com
gráficos 2D, em pixel art, de modo a aumentar a quantidade de profissionais que
poderiam criar e comercializar suas artes no jogo; afinal, a quantidade de
artistas 2D é muito superior àqueles com experiência em modelagem e animação 3D.

A questão, então, se torna: que tipo de gráfico, de forma concreta, se adequaria
melhor aos objetivos do TaeMOBA? Gráficos extremamente detalhados podem ser
muito atraentes visualmente, porém podem aumentar demais a barreira de entrada
para artistas interessados. De forma similar, a quantidade de direções que um
personagem pode "olhar" pode alterar significativamente os custos de criar uma
skin nova. Por exemplo, em jogos como Ragnarok Online, cada pose precisa ser
criada em 5 posições diferentes: baixo, baixo-esquerda, esquerda, cima-esquerda,
cima (as 3 posições olhando para a direita são espelhadas).

![ragnarok](https://i.imgur.com/fyokCpt.png)

O resultado disso é um gráfico extremamente atraente, porém, com custos de
produção, no mínimo, 5x elevados. Um outro extremo seria o de ter apenas uma
direção: esquerda. Inicialmente, um gráfico assim soa rígido e inviável, porém,
é possível fazer funcionar de uma forma bem engajante, principalmente utilizando
efeitos inteligentemente. um exemplo disso é o "among us", que, obviamente, não
é o jogo mais apelativo visualmente, porém tem uma identidade visual simples e
palatável que certamente fez parte do seu sucesso.

https://i.imgur.com/hFbEmEs.mp4

No caso do TaeMOBA, porém, um estilo um pouco mais "afiado" faz mais sentido
para mim. Um bom exemplo que se aplica bastante, tanto personagem quanto
ambiente, é o "Wizard of Legend". No caso, os personagens possuem 3 direções
(cima, esquerda e baixo), porém, não é difícil imaginar como poderia funcionar
com uma direção só. Esse exemplo é bem interessante pois ele é mais sério e
dark, o que se adequa mais a um jogo competitivo. Além do que, a ausência de
outlines e pouco sombreamento (apenas 2 tons de luz) simplificam a produção.

https://i.imgur.com/TldxoYA.mp4

No que se trata de animações de combate, uma inspiração que eu acho extremamente
pertinente é o Fire Emblem, na sua fase pixel art. Os personagens em si, apesar
de terem baixa resolução, são detalhados demais (perceba a quantidade de tons de
sombreamento), então, nesse aspecto, não se aplica. Porém, a animação em si, é
extremamente relevante, por dois motivos: 1. ela passa uma sensação de dimanismo
e poder; 2. isso é feito com uma quantidade baixíssima de frames!

![lyncritgif](https://i.imgur.com/ZEACDhl.gif)

![florinacritgif](https://i.imgur.com/J4nRSHM.gif)

![assassingif](https://s3-forums.serenesforest.net/monthly_2018_06/Assassin.gif.e5a4ff0fd3fb3bb0a6adff826a697710.gif)

Mas como é possível passar tanto dinamismo, com tão poucos frames? Se
analisarmos as sprite sheets, conseguimos notar fatores essenciais.

![lyncritsheet](https://i.imgur.com/rFCUupf.png)

1. **Keyframes cirúrgicos**: o personagem é desenhado em poucas poses (essa
   animação inteira tem apenas 4 poses!), porém, as poses escolhidas são
   justamente as mais pivotais para o movimento. Por exemplo, no primeiro gif, o
   momento em que a espada está maximamente virada para trás se tornou um
   keyframe. Esse efeito não só diminui os custos e facilita a comunicação
   visual, como também pode ser usado para causar a sensação de impacto. Por
   exemplo, no segundo gif, o momento em que a pegasus-knight acerta o arqueiro
   com a lança é um único keyframe que fica "parado" por mais de um segundo (!),
   destacando o impacto do momento.

2. **Transições via motion blur**: a transição entre 2 keyframes é, quase
   sempre, feita via motion blur. Por exemplo, do frame 0 para o frame 2, não
   existem frames intermediários levando a espada da "bainha" até a posição onde
   ela está maximamente virada para trás. Ao invés disso, apenas um "vulto" é
   desenhado, representando, em um único frame, todo o movimento de saque. De
   fato, isso é tão utilizado que os movimentos mais rápidos são feitos sem nem
   desenhar o personagem! Por exemplo, as duas "espadadas" são representadas
   pelo motion blur da espada, sem qualquer pose desenhada.

3. **Animação de tecidos e cabelos durante keyframes.** Por mais que frames
   congelados "passem" ao animar nossos heróis (afinal, o corpo deles se movem a
   uma velocidade altíssima!), essa "desculpa" não cola para partes "mortas"
   coladas ao corpo dos personagems, ou seja, cabelos e tecidos. Repare como o
   cabelo e roupa do primeiro personagem é animado durante os frames congelados.
   Isso não só recupera a fluidez "perdida" pelo uso de poucos frames, como
   acaba aumentando a sensação de velocidade; afinal, se o cabelo está demorando
   para voltar para a posição de repouso, isso significa que o personagem chegou
   lá de forma extremamente ágil.

Para o ambiente (mapa/ambiente/background), eu imagino algo com cores mais
"soft" e "pastel", poucos detalhes e baixa complexidade. Isso será extremamente
importante para destacar os personagens do fundo; ou seja, evitando com que a
tela se torne "poluida demais". Por exemplo, considere o jogo "Rivals of
Aether", que, sem dúvidas, tem gráficos lindos, porém, em certos momentos, se
torna difícil de encontrar os personagens na tela. Analise a imagem abaixo e
responda rápido: quantos personagens tem na tela?

![rivals](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTJff18AlPRwRPeZq3yZ5IMo32Z_xiINkJbABhg1tkwwD8f_IWhdiapVhRkSV3ZlDMb-eY&usqp=CAU)

Talvez você tenha notado os 4 personagens presentes, porém, não há como negar
que o background tornou essa tarefa muito mais difícil que deveria. Compare, por
exemplo, com o Among Us:

![amongfundo](https://www.emulatorpc.com/wp-content/uploads/2021/03/among-us-squad-1024x576-1.jpg)

A simplicidade dos gráficos do Among torna extremamente simples de separar os
bonecos do fundo, e "entender o que está acontecendo". Por isso, no caso do
TaeMOBA, devemos manter um mapa/ambiente simples e com cores pasteis,
destacando, assim, os personagens e objetos do jogo. Uma ideia que me vem a
cabeça é fazer o fundo inspirado em desenhos como Adventure Time e Steven
Universe, cujas paletas de cores conseguem passar imagens esteticamente
atraentes, sem muita complexidade visual.

![steven](https://i.imgur.com/tDp5KIc.png)

Em resumo, ainda estou estudando o melhor gráfico para a proposta do TaeMOBA,
porém, inicialmente, o que tenho em mente é um gráfico 2D, com um fundo simples,
soft e pastel, e personagens olhando apenas para uma direção (frente), com
sombreamento simplificado, e animações fluidas com poucos keyframes e abuso de
motion-blur para causar sensação de velocidade, impacto e poder. 
