# Tráfego Aéreo das Companhias Brasileiras em 2020

* O ano de 2020 foi marcado principalmente pela pandêmia do corona virus que atingiu proporções globais. Para o setor de aviaçõa e tráfego aéreo não foi diferente. O medo da contaminação dentro das aeronaves, o fechamento de fronteiras e a suspensão por parte dos governos de grande parte das operações das companhias aéreas são alguns dos fatores que contribuiram para a diminuição na demanda de transporte aéreo por parte da população. 

## Abstrato

* Os modelos de precificação das companhias aéreas não estavam preparados para o evento COVID 19, porque não possuíam dados historícos para acomodar a variável corona vírus. A queda na demanda provocou a queda no preço das passagens com trechos em que os preços atingiram os incríveis 6 dólares entre New Jersey e Florida. 

* Como o número de passageiros é uma variável de contagem ao longo do tempo, um modelo linear generalizado com a distribuição de Poisson parece adequado para acomodar a flutuação da demanda em futuras pandemias. 

* O objetivo da construção deste modelo foi orientar as companhias aéreas na tomada de decisão sobre a suspensão ou funcionamento de rotas e aeronaves baseado no custo-benefício da operação frente a uma nova pandêmia global. A demanda de número de passageiros foi ajustada em função do número de mortes e casos acumulados, bem como o número de novos casos e novos casos acumulados com intuito de que essas variáveis pudessem modelar a diminuição de passageiros e assim servir como ferramenta para futuros ajustes na operação.

## Introdução

* O presente trabalho foi desenvolvido com o objetivo de aplicar as técnicas ensinadas no curso _"Introdução aos Grafos Aleatórios"_ do Departamento de Estatística da UFMG. O tema escolhido para o trabalho foi “Volume de passageiros na covid 19” e o modelo escolhido foi o modelo de gravidade do capítulo 10 _"Fluxo de Redes"_  do livro  _"Statistical Analysis of Network Data"_.

* Partindo da concepção de ignorância dos algorítimos em relação aos eventos nunca registrados surgiu o interesse em investigar como seria possível incorporar esse tipo de evento nos modelos de precificação das companhias aéreas. É claro que o presente trabalho é apenas um exercício e não pode ser usado para objetivos tão sérios, mas pode funcionar bem como exercício prático do conteúdo ensinado.

* Os dados sobre o covid foram coletados no sítio “ourworldindata” e os dados do número de passageiros foram coletados  no sitio da ANAC ver referências. 

* Os dados foram limpos e processados para serem utilizados na análise descritiva e modelagem.

* A etapa da análise descritiva foi elaborada usando estatística do universo de grafos e técnicas de visualização da rede de fluxo de passageiros entre países.

* A modelagem foi realizada utilizando modelos lineares generalizados considerando a distribuição Poisson.

* Finalmente as conclusões indicaram que de fato as variáveis escolhidas foram estatisticamente significativas para a modelagem do número de passageiros.

* A modelagem do problema foi implementada no ambiente de prototipagem R utilizando os pacotes `tidyverse` , `igraph` , `lubridate` , `DT` , `naniar` , `shiny` , `broom` , `geosphere` , `gridExtra`.
