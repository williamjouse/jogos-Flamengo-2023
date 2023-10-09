## Dados do Flamengo 2023

Tabelas com informações sobre os jogos do Flamengo no ano de 2023. A tabela [matches_FLA2023.csv](https://github.com/williamjouse/jogos-Flamengo-2023/blob/main/data/matches_FLA2023.csv)
contém as seguintes colunas:

- id_match: ID do jogo
- home_team: Time mandante
- away_team: Time visitante
- home_score: Gols marcado pelo mandante
- away_score: Gols marcado pelo visitante
- tournament: Torneio ou competição e rodada
- kick-off: Data e hora da partida
- stadium: Estádio da partida


Na segunda tabela de nome [goal_scorers.csv](https://github.com/williamjouse/jogos-Flamengo-2023/blob/main/data/goal_scorers.csv) contém as seguites colunas:

- id_match: ID do jogo
- gols: Jogadores que fizem gols na partida
- assist: Assistência para o gol


No arquivo [matches_FLA2023.xlsx](https://github.com/williamjouse/jogos-Flamengo-2023/blob/main/data/matches_FLA2023.xlsx) contém a junção das 2 tabelas em um único lugar.

A análise é feita no [Jupyter notebook](https://github.com/williamjouse/jogos-Flamengo-2023/blob/main/notebooks/01-New_Analysis.ipynb) onde é produzido as tabelas e figuras.




### Algumas estatísticas

| Jogador           |   Gols |   Assistências |
|:------------------|-------:|---------------:|
| Pedro             |     28 |              4 |
| Gabi              |     20 |              3 |
| Arrascaeta        |      8 |             12 |
| Bruno Henrique    |      7 |              1 |
| Ayrton Lucas      |      6 |              5 |
| Gerson            |      5 |              9 |
| Everton Cebolinha |      4 |              8 |
| Léo Pereira       |      4 |              2 |
| Victor Hugo       |      3 |              2 |
| Matheus França    |      3 |              0 |
| Thiago Maia       |      3 |              0 |
| Fabrício Bruno    |      3 |              0 |
| Matheus Gonçalves |      2 |              0 |
| Everton Ribeiro   |      2 |              6 |
| Eric Pulgar       |      2 |              2 |


```
Jogos: 64
Vitórias: 34
Empates: 14
Derrotas: 16 
Gols pro: 107
Gols contra: 69
Saldo de gols: +38
Gols/jogo: 1.67
Gols sofridos/jogo: 1.08
Jogos em que marcou: 52
Jogos em que sofreu gol: 39 
Aproveitamento: 60.42%
Aproveitamento pontos: 116/192
```
----


![img1.png](notebooks/figures/figure.png)

![img1.png](notebooks/figures/figure2.png)

![img1.png](notebooks/figures/figure3.png)

![img1.png](notebooks/figures/figure4.png)

![img1.png](notebooks/figures/figure7.png)


### Referências e Dados

- [Sofascore](https://www.sofascore.com/)
- [O Goal](https://www.ogol.com.br)
- [ge](https://ge.globo.com/)