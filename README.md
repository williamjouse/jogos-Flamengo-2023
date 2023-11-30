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
| Pedro             |     34 |              4 |
| Gabi              |     20 |              3 |
| Arrascaeta        |     11 |             12 |
| Ayrton Lucas      |      7 |              7 |
| Bruno Henrique    |      7 |              2 |
| Gerson            |      6 |             10 |
| Everton Cebolinha |      6 |             10 |
| Léo Pereira       |      4 |              2 |
| Victor Hugo       |      3 |              2 |
| Everton Ribeiro   |      3 |              7 |
| Matheus França    |      3 |              0 |
| Thiago Maia       |      3 |              0 |
| Fabrício Bruno    |      3 |              0 |
| Matheus Gonçalves |      2 |              0 |
| Eric Pulgar       |      2 |              5 |





```
Jogos: 74
Vitórias: 40
Empates: 15
Derrotas: 19 
Gols pro: 123
Gols contra: 78
Saldo de gols: +45
Gols/jogo: 1.66
Gols sofridos/jogo: 1.05
Jogos em que marcou: 61
Jogos em que sofreu gol: 43 
Aproveitamento: 60.81%
Aproveitamento pontos: 135/222
```
----


![img1.png](notebooks/figures/figure.png)

![img1.png](notebooks/figures/figure2.png)

![img1.png](notebooks/figures/figure3.png)

![img1.png](notebooks/figures/figure4.png)

![img1.png](notebooks/figures/figure8.png)


### Referências e Dados

- [Sofascore](https://www.sofascore.com/)
- [O Goal](https://www.ogol.com.br)
- [ge](https://ge.globo.com/)