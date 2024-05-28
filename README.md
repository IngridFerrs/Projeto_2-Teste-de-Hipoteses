# Projeto 2- Teste de Hipótese
No cenário competitivo e dinâmico da indústria musical, a capacidade de tomar decisões embasadas em dados é crucial. Este projeto surge no contexto desafiador de uma gravadora que busca lançar um novo artista no cenário global. Utilizando um extenso conjunto de dados contendo informações sobre as músicas mais ouvidas em 2023, a gravadora formula diversas hipóteses para compreender os padrões de sucesso.

As hipóteses levantadas abrangem uma variedade de aspectos, desde características musicais até comportamento de consumo em diferentes plataformas. Entre elas, destacam-se a possível correlação entre o número de streams e o BPM das músicas, a similaridade de desempenho entre as principais faixas do Spotify e outras plataformas como Deezer, e a influência da inclusão em playlists na popularidade de uma música.

O projeto utiliza uma abordagem analítica para refutar ou confirmar essas hipóteses, empregando ferramentas como **BigQuery** para manipulação de dados via SQL, **Python** para análise estatística e **PowerBI** para visualização e interpretação dos resultados. O objetivo final é gerar insights estratégicos que possam orientar decisões eficazes no lançamento de novos artistas e no gerenciamento do catálogo musical da gravadora.


# Conclusões e Insights:

| Tópico                                | Conclusão                                                                                                                                                |
|---------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| :bar_chart: Distribuição Não Paramétrica          | A distribuição dos dados não é normal, exigindo métodos não paramétricos. Recomenda-se o uso do teste de Mann-Whitney.                                   |
| :musical_note: Características Musicais e Sucesso    | A maioria das características musicais não demonstram relação significativa com o sucesso. Exceções incluem "speechiness", "danceability" e "valence". |
| :musical_note: BPM e Sucesso Musical                 | Não há uma relação linear clara entre o BPM e o sucesso da música.                                                                                       |
| :computer: Correlação entre Plataformas de Streaming | Existe uma correlação moderada positiva entre a presença nas plataformas de streaming. O sucesso em uma plataforma pode influenciar positivamente outras. |
| :headphones: Presença em Playlists e Sucesso       | A presença em playlists está fortemente correlacionada com o sucesso.                                                                                    |
| :cd: Quantidade de Músicas e Sucesso       | A quantidade de músicas lançadas influencia diretamente o sucesso. Aumentar o catálogo de músicas pode aumentar as chances de sucesso.                               |
| :chart_with_upwards_trend: <span style="color:green">**Estratégia de Lançamento**</span>              | <span style="color:green">**Uma estratégia eficaz deve considerar características musicais, presença em playlists, distribuição entre plataformas de streaming e estratégias de marketing integradas.**</span> |


