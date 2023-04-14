# WebScrapingFutebol
Este projeto tem como objetivo coletar dados sobre jogos de futebol em todo o mundo e utilizá-los para prever os resultados dos jogos com relação a Under Gols, Over Gols e ambas as equipes marcam.

A coleta de dados é feita a partir do site soccerstats.com utilizando a biblioteca requests do Python para fazer requisições HTTP e obter o código HTML da página. Em seguida, a biblioteca pandas é utilizada para ler os dados em formato de tabela a partir do código HTML.

Os dados coletados são tratados e organizados em diferentes tabelas, cada uma com informações específicas sobre os jogos, tais como: país, equipes envolvidas, horário do jogo, média de gols marcados e sofridos, entre outras.

As tabelas são então combinadas para criar tabelas mais completas com informações sobre as equipes e seus históricos, tornando possível realizar previsões sobre os resultados dos jogos com relação a Under Gols, Over Gols e ambas as equipes marcam.
