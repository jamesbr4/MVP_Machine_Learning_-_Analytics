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

<h1><b> Área de Aplicação </b></h1>
Este projeto de análise e previsão de preços de ações pode ser aplicado em diversas áreas, principalmente dentro do domínio financeiro e de investimentos:<br>

<b>Gestão de Portfólio de Investimentos:</b> Investidores e gestores de fundos podem usar as previsões para tomar decisões sobre quais ações comprar, vender ou manter, buscando maximizar retornos e minimizar riscos.<br>
<b>Análise de Risco:</b> As análises de volatilidade e Value at Risk (VaR) ajudam a quantificar e gerenciar o risco associado a investimentos em ações específicas ou a um portfólio.<br>
<b>Algorithmic Trading (Negociação Algorítmica):</b> As previsões geradas pelos modelos podem ser usadas como sinais de entrada/saída para sistemas de negociação automatizados.<br>
<b>Pesquisa Financeira:</b> O projeto serve como base para pesquisas acadêmicas ou industriais sobre o comportamento do mercado de ações, a eficácia de diferentes modelos de previsão e os fatores que influenciam os preços.<br>
<b>Educação Financeira:</b> O notebook pode ser usado como uma ferramenta educacional para demonstrar conceitos de análise de mercado, modelagem de séries temporais e finanças quantitativas.<br>
<b>Tomada de Decisão Corporativa:</b> Empresas de capital aberto podem analisar o comportamento de suas próprias ações ou as de concorrentes para entender o sentimento do mercado e planejar estratégias financeiras.<br>

<h1><b> Valor para o Negócio </b></h1>
Este projeto pode trazer um valor significativo para um negócio, especialmente aqueles envolvidos com o mercado financeiro ou que precisam tomar decisões baseadas no desempenho de ações.<br>
O valor reside principalmente em:<br>
<b>Melhor Tomada de Decisão de Investimento:</b> Ao fornecer análises sobre o comportamento histórico das ações, volatilidade, risco (VaR) e correlação, o projeto permite que gestores de investimento ou analistas tomem decisões mais informadas sobre onde alocar capital. As previsões de preços podem ajudar a identificar potenciais oportunidades de compra ou venda.<br>
<b>Gerenciamento de Risco Aprimorado:</b> A quantificação do risco diário (VaR) para ações específicas ajuda a entender a perda potencial máxima em um determinado nível de confiança. Isso é crucial para gerenciar a exposição ao risco de um portfólio e tomar medidas de mitigação.<br>
<b>Otimização de Estratégias de Negociação:</b> Para negócios que utilizam negociação algorítmica, as previsões de preços podem ser incorporadas em estratégias automatizadas para gerar sinais de negociação, buscando capitalizar movimentos de mercado previstos.<br>
<b>Entendimento do Mercado:</b> A análise exploratória fornece insights sobre as tendências do mercado de tecnologia, a volatilidade relativa de diferentes ações e como elas se movem em relação umas às outras. Isso ajuda o negócio a ter uma compreensão mais profunda do ambiente em que opera.<br>
<b>Desenvolvimento de Produtos/Serviços:</b> Empresas de tecnologia financeira (FinTech) podem usar as análises e modelos desenvolvidos como base para criar produtos ou serviços relacionados a ferramentas de análise de investimento, consultoria automatizada (robo-advisors) ou plataformas de negociação.<br>
<b>Alocação Eficiente de Recursos:</b> Ao entender melhor o risco e o retorno potencial de diferentes ações, um negócio pode alocar seus recursos financeiros de forma mais eficiente, investindo em ativos que se alinham com seus objetivos de risco e retorno.<br>

<h1><b> Seleção de Dados </b></h1>

<h1><b> Atributos do dataset</b></h1>

<h1>Conclusão</h1>
