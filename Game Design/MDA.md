O MDA é um framework de game design criado em 2004 por Robin Hunicke, Marc LeBlanc e Robert Zubek. Esse framework foi criado para ser uma abordagem formal para entender jogos, ajudando qualquer um a decompor, estudar e projetar qualquer jogo.
Os pesquisadores partiram do principio básico de que os jogos são criados por designers e consumidos por jogadores.
![[MDA - 01.png]]
E que o consumo desse produto é relativamente imprevisível e por isso a estrutura do MDA formaliza o consumo dos jogos, dividindo-os em seus componentes específicos:
> [!IMPORTANT] M de Mechanics
> Descreve as regras, as limitações e também o conteúdo do jogo (níveis, skins, etc)

> [!IMPORTANT] D de Dynamics
Descreve como o jogador usa as regras para avançar e as estratégias que emergem dessas regras.

> [!IMPORTANT] A de Aesthetics
> Descreve as respostas emocionais desejáveis evocadas no jogador, quando ele interage com o sistema do jogo.

Designers e jogadores percebem o jogo por perspectivas diferentes. Os designers criam mecânicas que dão origem ao comportamento dinâmico que por sua vez leva a experiências estéticas particulares. Já do ponto de vista do jogador, a estética defini o tom que nasce dás dinâmicas e da mecânicas.
![[MDA_04.png]]
É interessante enxergar os jogos como sistemas que constroem o comportamento por meio da interação, por que isso auxilia escolhas de design e análises mais claras em todos os níveis de estudo e desenvolvimento.

# Taxonomia dos Prazeres de LeBlanc
Ao descrever a estética de um jogo é interessante nos afastarmos de palavras muito abstratas como "diversão" em troca de um vocabulário mais direcionado. Para contribuir com isso LeBlanc criou a seguinte taxonomia:
###### 1. Sensação
Jogo como prazer dos sentidos.
###### 2. Fantasia
jogo como faz de conta.
###### 3. Narrativa
Jogo como drama.
###### 4. Desafio
Jogo como pista de obstáculos.
###### 5. Companheirismo
Jogo como contexto social.
###### 6. Descoberta
Jogo como território não mapeado.
###### 7. Expressão
Jogo como autodescoberta.
###### 8. Obediência
Jogo como passatempo.

Essas são os oito prazeres listados originalmente, mas existem muitos outros, como por exemplo o "medo", que é o principal prazer na estética de jogos de terror ou a "inteligência", que é o prazer que carrega os thinky games.

# Exemplos do uso do MDA
## Mario
###### Mecânicas
- Andar/Correr.
- Pular.
- Morte ao cair em buracos.
###### Dinâmica
- Ao encontrar um buraco o jogador corre e pula para o outro lado.
###### Estética
- Desafio.
## Valorant
###### Mecânicas
- Atirar.
- Tiros na cabeça causam mais dano.
###### Dinâmicas
- Jogadores habilidosos miram na cabeça para conseguir eliminar a ameaça com mais eficiência.
###### Estética
- Desafio.
- Masterização.
## Overcooked
###### Mecânicas
- Alimentos podem ser cortados, batidos, cozinhados e fritos, mas em lugares diferentes.
- O objetivo do jogador é servir a comida que o cliente pediu.
- Clientes dão menos gorjeta se a comida demorar.
- Cada nível tem um curto limite de tempo.
- O jogo dá uma nota maior para jogadores que entregarem mais pedidos dentro do tempo.
- Os alimentos estão longe um dos outros.
- O cenário se modifica impedindo que um jogador consiga acessar todos os alimentos.
###### Dinâmicas
- Os jogadores se comunicam e coordenam suas ações.
###### Estética
- Companheirismo/Trabalho em Equipe.

# Mais
- A gente pode tentar planejar a estética, mas ela não está nas mãos dos designers, ela acontece na cabeça do jogador.
- Resumo geral do MDA: O M é tudo que o jogo é sem a interação que vêm do jogador. Tudo que nasce dessa interação vai para o D, e todo sentimento que o D gera é um E.

# Fontes
- [[MDA - Original.pdf]]
- [[MDA - PTBR.pdf]]
- https://www.youtube.com/watch?v=SRfyF9741SY&t=4102s&ab_channel=GameDevToolkit
- https://youtu.be/uepAJ-rqJKA