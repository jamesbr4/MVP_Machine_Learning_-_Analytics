# MVP_Machine_Learning_&_Analytics
Projeto MVP do MBA Ciência de Dados e Analytics PUC-Rio

<h1><b> Descrição do Problema </b></h1>
Análise e previsão dos preços de fechamento de ações de tecnologia utilizando dados históricos.
O projeto busca:
1) Analisar o comportamento histórico dos preços e volume de negociação de um conjunto de ações de tecnologia.
2) Entender o risco e a correlação entre os retornos diários dessas ações.
3) Desenvolver e comparar modelos (como Baseline, ARIMA e LSTM) para prever os preços de fechamento futuros com base nos dados passados.

<h1><b> Perguntas do Problema </b></h1>

1. Qual foi a variação do preço das ações ao longo do tempo?
  <br>R: A variação do preço das ações ao longo do tempo, conforme mostrado no gráfico, foi predominantemente uma tendência de alta para a maioria das ações de tecnologia no período analisado, mas com diferentes níveis de volatilidade e padrões de movimento para cada ação individualmente.<br>
2. Qual foi a média móvel das diversas ações?
  <br>R: As médias móveis fornecem uma perspectiva suavizada do movimento dos preços das ações ao longo do tempo, ajudando a identificar e confirmar tendências de curto e longo prazo para cada uma das ações analisadas. A escolha do período
da média móvel influencia a sensibilidade do indicador às mudanças de preço. Sendo de 10 a 15 dias para curto prazo e 45 e 60 dias para longo prazo.<br>
3. Qual foi o retorno diário médio da ação?
  <br>R: Com base na visualização da distribuição, podemos concluir que o retorno diário médio para a maioria dessas ações de tecnologia no período de janeiro de 2020 a agosto de 2025 foi próximo a zero. A diferença entre as ações se manifesta mais na volatilidade (largura da distribuição) do que no retorno médio diário em si para este período específico.<br>
4. Qual foi a correlação entre os preços de fechamento de diferentes ações?
  <br>R: O gráfico de calor demonstra visualmente que houve uma alta correlação positiva entre os preços de fechamento das diversas ações de tecnologia no período, significando que elas tenderam a se mover na mesma direção geral no mercado.<br>
5. Quanto valor colocamos em risco ao investir em uma ação específica?
  <br>R: O valor do VaR (Value at Risk) calculado para cada ação na tabela representa uma estimativa da perda potencial máxima que você poderia experimentar em um único dia, com 95% de confiança. Ele quantifica o "valor em risco" histórico em termos monetários (USD) e percentuais, dando uma medida concreta do risco de queda para cada ação.<br>
6. Previsão do preço de fechamento das ações
  
<h1><b> Tipo de Problema </b></h1>

Este é um problema de Previsão de Séries Temporais.

<h1><b> Seleção de Dados </b></h1>

<h1><b> Atributos do dataset após tratamento dos dados</b></h1>

<h1>Conclusão</h1>
