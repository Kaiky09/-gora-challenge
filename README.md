Repositório referente a participação no Ágora Challenge 2023.

O Ágora Challenge 2023 foi um desafio em grupo de asset manegement em 6 rodadas. O objetivo era obter o maior bônus acumulado no fim das 6 rodadas e os 5 primeiros colocados avançavam para a fase final.
Todos os grupos iniciavam com o mesmo capital que poderia ser investido no começo da rodada. No fim da rodada, o Índice de Sharpe da carteira era calculado e um bônus proporcional era dado ao grupo.

As rodadas representavam a passagem de 1 ano num mundo fictíceo, de forma que os grupos eram residentes do país Lokal. O capital era investido de acordo com a carteira montada pelo grupo no dia primeiro de janeiro e realizado no dia 31 de dezembro. Os ativos disponíveis eram:  7 ações, 2 títulos de renda fixa, 2 contratos futuros de câmbio de moeda estrangeira.
As ações representavam alguns setores da economia. A renda fixa era pública, sendo um pós-fixado de 1 ano e o outro pré-fixado de 2 anos. 

Além disso, eram enviadas notícias ano a ano acerca da economia do país e do cenário intercional, o que impactava na expectativa dos grupos e suas alocações. Todos os ativos e seus preços eram ficitíceos e os dados sobre preços diários eram disponibilizados a cada rodada, assim foi montada a base 'agora' disponibilzada.

Meu grupo, denominado Gasset, teve como estratégia partir de uma alocação 'ingênua' de modelos de otimização de portifólio e refinar essas alocações a partir das nossas crenças acerca dos movimentos de preços. Por exemplo, se uma ação vinha com um histórico de boa performance, mas havia uma perspectiva negativa para o ano seguinte, o modelo colocaria um peso muito grande nela e nós reduziríamos.

Começamos com o modelo de Markowitz, então, com a necessidade de incluir nossas expectativas no modelo, utilizamos o modelo de Black-Litterman (B-L). Por fim, chegamos ao modelo HRP que utiliza um algoritimo de machine learning com uma estratégia baseada em volatilidade, que gera portifólios menos extremos que os dois primeiros modelos.

Infelizmente, não conseguimos atingir o top 5, devido ao nosso início um pouco fraco, o que teve um grande impacto porque o desafio tinha um 'efeito bola de neve'. Porém, foi uma jornada de muito desenvolvimento e aprendizado, comprovado pelo nosso grande ganho de posições, partimos de 68° colocado para 27°, sendo que, na última rodada, obtivemos o maior Sharpe entre os grupos.

Todas as análises foram feitas em Python, com alguns tratamentos iniciais em Excel.

Ao longo do tempo, irei postar os códigos de todas as rodadas. Vale notar, que os portifólios gerados nos códigos não foram os realmente alocados, já que ainda era feita um refino pelo grupo e uma ponderação do capital total entre risk-free (renda fixa pós) e a carteira final.

Segue um print do ranking de grupos ordenado por Sharpe da rodada na rodada 6, em que obtivemos melhor índice:
![sharpe-rodada-final](https://github.com/Kaiky09/agora-challenge/assets/84930783/ff9e119e-150d-47d7-a72d-395bf94ab7a1)
