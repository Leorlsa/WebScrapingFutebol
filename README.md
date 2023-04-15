# WebScrapingFutebol
Este projeto tem como objetivo coletar dados sobre jogos de futebol em todo o mundo e utilizá-los para prever os resultados dos jogos com relação a Under Gols, Over Gols e ambas as equipes marcam.

A coleta de dados é feita a partir do site soccerstats.com utilizando a biblioteca requests do Python para fazer requisições HTTP e obter o código HTML da página. Em seguida, a biblioteca pandas é utilizada para ler os dados em formato de tabela a partir do código HTML.

Os dados coletados são tratados e organizados em diferentes tabelas, cada uma com informações específicas sobre os jogos, tais como: país, equipes envolvidas, horário do jogo, média de gols marcados e sofridos, entre outras.

As tabelas são então combinadas para criar tabelas mais completas com informações sobre as equipes e seus históricos, tornando possível realizar previsões sobre os resultados dos jogos com relação a Under Gols, Over Gols e ambas as equipes marcam.
<hr>

## Pegando a Tabela do site:
![image](https://user-images.githubusercontent.com/79804184/232244950-b8ce0255-918d-426d-a378-76779c5b624c.png)

<hr>

## Jogos de hoje:
![image](https://user-images.githubusercontent.com/79804184/232244980-4f1ae0a3-bc1d-4922-ab88-0ad7d37841a2.png)
##### jogos_today.to_excel("Jogos de Hoje.xlsx") Baixando Planilha de excel, mostrando jogos do dia e estatísticas.

<hr>

## Estratégia Under Gols/Planilha
![image](https://user-images.githubusercontent.com/79804184/232245149-696cdd03-a3b2-490f-9c6e-3fe63bf56a79.png)

<hr>

## Estratégia Over Gols/Planilha
![image](https://user-images.githubusercontent.com/79804184/232245202-847338a8-7826-4078-8b17-f41fc2f2aa54.png)

<hr>

## Estratégia Ambas Marcam/Planilha
![image](https://user-images.githubusercontent.com/79804184/232245299-32a7c066-2896-4b12-8946-f7a5f3f04cf3.png)



