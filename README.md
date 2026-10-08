# ICE — análise de mercado de games
Projeto de análise de dados voltado à identificação de padrões de vendas no mercado de videogames e à construção de recomendações para uma campanha comercial de 2017, desenvolvido na formação de Analista de Dados da TripleTen.

**English summary.** Analysis of historical video game sales to identify the platforms, genres and regional markets with the most potential for a 2017 campaign, covering platform life cycles, recent trends, review scores and regional profiles for North America, Europe and Japan. PS4 and Xbox One showed the strongest recent trend; critic scores had a small positive association with sales, while user scores had none. Hypothesis tests found a difference in average user ratings between Action and Sports, but not between Xbox One and PC. Project developed as part of TripleTen's Data Analyst program.

## Objetivo

Avaliar quais plataformas, gêneros e mercados regionais apresentavam maior potencial, considerando tendências recentes de vendas, ciclo de vida das plataformas, avaliações de usuários e críticos e diferenças entre América do Norte, Europa e Japão.

## Ferramentas

- Python
- pandas
- seaborn
- scipy
- Jupyter Notebook

## Principais análises

- preparação e validação dos dados;
- evolução histórica de lançamentos e vendas;
- ciclo de vida e tendências de plataformas;
- comparação de desempenho entre plataformas;
- relação entre avaliações e vendas;
- perfis regionais por plataforma, gênero e classificação ESRB;
- testes de hipótese sobre avaliações de usuários.

## Principais achados

- PS4 e Xbox One aparecem como plataformas com melhor tendência recente para a campanha analisada;
- os perfis de plataforma e gênero variam de forma relevante entre os mercados ocidentais e o Japão;
- avaliações de usuários não apresentam relação clara com vendas, enquanto avaliações de críticos mostram associação positiva pequena;
- não houve evidência suficiente de diferença entre as avaliações médias de Xbox One e PC;
- houve evidência estatística de diferença entre as avaliações médias dos gêneros Action e Sports.

## Dados

O dataset não é redistribuído neste repositório. Para executar o notebook localmente, coloque `games.csv` em `data/`.

Os outputs foram mantidos no notebook para que a análise possa ser visualizada diretamente no GitHub.
