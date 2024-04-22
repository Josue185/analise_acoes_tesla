# analise_acoes_tesla

Entendendo a Análise de Dados Financeiros com Gráficos Interativos
Imagina que você está interessado em entender como as ações da Tesla se comportaram nos últimos dois anos. Você quer saber em quais momentos as ações estavam em alta ou quando tiveram uma queda significativa. Para isso, decidimos usar uma ferramenta poderosa chamada Apache Spark, que nos ajuda a analisar grandes quantidades de dados rapidamente, mesmo que esses dados sejam complexos ou muito extensos.

O Primeiro Passo: Pegar os Dados
Nós começamos obtendo informações sobre os preços diários das ações da Apple diretamente de uma fonte confiável como o Yahoo Finance. Esse site nos fornece uma série de dados, como o preço mais alto e mais baixo de cada dia, e o preço de fechamento – que é o valor da ação no final do dia de negociação.

Preparando os Dados para Análise
Depois de coletar esses dados para os anos de 2023 e 2024, nós os organizamos de maneira que pudéssemos trabalhar com eles no Spark. Isso envolve um processo de transformação dos dados brutos em um formato que o Spark pode entender e manipular eficientemente.

Analisando as Diferenças
O objetivo principal aqui é comparar como os preços se comportaram entre dois anos diferentes. Para isso, utilizamos um tipo de gráfico chamado "gráfico de área sobreposta". Imagine que cada ano é representado por uma cor diferente em um gráfico. Onde as cores se sobrepõem, significa que os preços estavam relativamente próximos nesses dias. Onde uma cor predomina, mostra que houve uma grande diferença no preço das ações entre um ano e outro.

Esse tipo de visualização é excelente para identificar rapidamente períodos de grande variação, como uma alta súbita ou uma queda nas ações, e também para ver tendências ao longo do tempo, como se os preços estão geralmente subindo ou descendo ao longo dos anos.
![Comparando as ações da Tesla 2023](https://github.com/Josue185/analise_acoes_tesla/assets/92592495/45a08c35-64c6-4a46-9fbe-aceaedac49fe)

![Comparando as ações da Tesla 2024](https://github.com/Josue185/analise_acoes_tesla/assets/92592495/ee610b19-1626-4f12-86e1-7bac9b2e6eb8)

Conclusão
Com essa análise, você não apenas vê números frios, mas obtém uma história visual do comportamento das ações. Isso pode ajudar investidores, analistas ou apenas curiosos a entenderem melhor os mercados e a tomarem decisões mais informadas baseadas em como os eventos ou as condições de mercado afetaram os preços anteriormente.
