# Analise-exploratoria-de-imoveis-da-uniao

Análise exploratória de dados com base em dados abertos do Governo Federal para identificar imóveis pertecentes à União que possam ser úteis para destinação para Habitação de Interesse Social obtidos pelo link: https://dados.gov.br/dados/conjuntos-dados/imoveis-da-uniao

Em fevereiro de 2024 o Governo Federal anunciou que iria destinar os imóveis da União inutilizados para transformá-los em Habitação de Interesse Social, conforme a seguinte matéria explicita:

https://www.gov.br/gestao/pt-br/assuntos/noticias/2024/fevereiro/governo-lanca-programa-imovel-da-gente-com-75-imoveis-ja-destinados-ao-sudeste

O anúncio chamou atenção por se tratar de uma iniciativa interessante, haja vista que do ponto de vista econômico, se apresenta como uma medida eficiente, já que o governo não precisaria gastar dinheiro para construir novas residências, e do ponto de vista urbanistico também, tendo em vista que a depender da localização dos imóveis, as habitações podem se concentrar em áreas onde já existam infraestrutura para absorver a população que ali habita.

No entanto, hoje, em 2025, não se ouviu mais falar no andamento desta política pública, nem como estão os trâmites a respeito da destinação destes imóveis.

Em virtude disso, me chamou atenção buscar o dataset disponível no portal dados abertos para poder verificar quais imóveis identificados podem ser úteis para serem destinados para Habitação de Interesse Social, do ponto de vista urbanístico e econômico.

A intenção desta pesquisa exploratória é, portanto, com base nas aplicações teóricas de autores como Jane Jacobs (1961), Jan Gehl (2010) e Edward Glaeser (2010), de que o desenvolvimento de uma cidade deve partir de centros urbanos adensados, caminháveis, arborizados, e diversificados, dotado de imóveis de usos mistos, verificar quais são os imóveis pertecentes à União que possam satisfazer a este modelo de cidade.

Com a pesquisa exploratória realizada, após executar os processos de limpeza dos dados brutos e identificar os imóveis aptos para serem identificados como Habitação de Interesse Social, o dataframe foi reduzido até se obter uma dimensionalidade daqueles imóveis que pertencem às capitais, ou seja, são imóveis que existem em uma infraestrutura urbana já existente e pertencente a centros metropolitanos.

Não obstante foi necessário também identificar imóveis aptos para moradia, logo foram selecionados categorias de imóveis que se aplicam na lógica de moradia, isto é: Apartamentos, Casas e Hotéis.

Com essa segmentação dos dados foi possível chegar no resultado abaixo, onde apresenta a localidade dos imóveis que pertencem à União aptos para Habitação de interesse social.

![image](https://github.com/user-attachments/assets/cd4c1c17-0874-4dc6-849c-a6e236b9ae5e)
