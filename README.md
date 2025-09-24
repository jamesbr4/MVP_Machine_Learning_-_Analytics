# MVP_Machine_Learning_&_Analytics
Projeto MVP do MBA Ciência de Dados e Analytics PUC-Rio

<h1><b> Descrição do Problema </b></h1>
Análise e previsão dos preços de fechamento de ações de tecnologia utilizando dados históricos.<br>
O projeto busca:<br>
1) Analisar o comportamento histórico dos preços e volume de negociação de um conjunto de ações de tecnologia.<br>
2) Entender o risco e a correlação entre os retornos diários dessas ações.<br>
3) Desenvolver e comparar modelos (como Baseline, Random Forest, ARIMA e LSTM(Modelo Selecionado para gerar as predições)) para prever os preços de fechamento futuros com base nos dados passados.

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
  <br>R: O modelo LSTM, como um algoritmo de Deep Learning, conseguiu aprender padrões nos dados históricos para fazer previsões que geralmente acompanham a direção do mercado, mas está sujeito a erros e variações diárias, que são normais em previsões de séries temporais financeiras. A análise das métricas e a visualização gráfica ajudam a entender a magnitude desses erros e a confiança que podemos ter nas previsões.
  
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

Este conjunto de dados é composto por preços de ações e os dados são provenientes do YFinance (Yahoo Finance).

<h1><b> Atributos do dataset</b></h1>
<table>
        <tr>
            <th>Atributos</th>
            <th>Data Type</th>
            <th>Unidade</th>
        </tr>
        <tr>
            <td>Price</td>
            <td>object</td>
            <td>texto</td>
        </tr>
        <tr>            
            <td>Close</td>
            <td>float64</td>
            <td>$ (dólar)</td>            
        </tr>
        <tr>            
            <td>High</td>
            <td>float64</td>
            <td>$ (dólar)</td>            
        </tr>
        <tr>
            <td>Low</td>
            <td>float64</td>
            <td>$ (dólar)</td>
        </tr>
        <tr>
            <td>Open</td>
            <td>float64</td>
            <td>$ (dólar)</td>
        </tr>
        <tr>
            <td>Volume</td>
            <td>int64</td>
            <td>número</td>
        </tr>
        <tr>
            <td>company_name</td>
            <td>object</td>
            <td>texto</td>
        </tr>
        <tr>
            <td>Ticker</td>
            <td>object</td>
            <td>texto</td>
        </tr>
        <tr>
            <td>Date</td>
            <td>object</td>
            <td>data (YYYY-MM-DD)</td>
        </tr>
    </table>
<h1><b>Conclusão</b></h1>
Este projeto realizou uma análise exploratória e modelagem preditiva dos preços de fechamento de um conjunto de ações de tecnologia (AAPL, GOOG, MSFT, AMZN, NFLX, SPOT) utilizando dados históricos de janeiro de 2020 a agosto de 2025.<br>

A análise inicial dos dados revelou tendências históricas de preços, padrões de volume de negociação e métricas descritivas importantes para cada ação. Exploramos a média móvel para suavizar as flutuações de preços e identificar tendências. A análise de retorno diário médio e Value at Risk (VaR) nos forneceu insights sobre o risco associado a cada ação no período analisado. A matriz de correlação destacou a alta correlação positiva entre os retornos diários da maioria das ações de tecnologia na carteira.<br>

Na fase de modelagem preditiva, foram comparados modelos Baseline (Média Móvel), Random Forest, ARIMA e LSTM. O modelo LSTM foi otimizado e o ARIMA também passou por otimização de hiperparâmetros (ordem p, d, q) usando o conjunto de validação antes de serem avaliados. As métricas de avaliação no conjunto de teste (MSE, RMSE, MAE) foram consolidadas para comparação.<br>

Com base no MSE médio no conjunto de teste, o ranking de desempenho dos modelos, do melhor para o pior, foi:<br>

1.  <b>ARIMA Otimizado:</b> Apresentou o menor MSE médio, indicando o melhor desempenho geral.<br>
2.  <b>LSTM:</b> Embora não tenha tido o menor MSE médio, demonstrou uma capacidade razoável de seguir a tendência e teve desempenho significativamente superior ao Baseline e Random Forest para a maioria das ações.<br>
3.  <b>Random Forest (Otimizado):</b> Teve um desempenho superior ao Baseline, mas geralmente inferior ao ARIMA Otimizado e LSTM em termos de MSE.<br>
4.  <b>Baseline (Média Móvel):</b> Como esperado, foi o modelo com o pior desempenho (maior MSE), servindo como um ponto de comparação simples.<br>

As tabelas de comparação entre os preços reais e previstos pela LSTM visualizam a capacidade do modelo de seguir a tendência geral dos preços, embora com variações e erros inerentes à previsão de séries temporais financeiras.<br>

<h1><b>Limitações do Projeto</b></h1><br>

É importante reconhecer as limitações deste projeto:<br>

1. <b>Modelos:</b> Os modelos utilizados (ARIMA com grade limitada e a arquitetura de LSTM) são relativamente simples e podem não capturar todas as complexidades e não linearidades do mercado de ações. Modelos mais avançados ou ensembles poderiam ser explorados.<br>
2. <b>Otimização do LSTM:</b> Embora a otimização de hiperparâmetros para o LSTM tenha sido realizada, a grade de busca utilizada pode ter sido limitada, e <b>uma otimização mais abrangente poderia levar a um modelo ainda mais preciso.</b><br>
3. <b>Recursos Utilizados:</b> O projeto focou apenas no preço de fechamento como principal característica de entrada para os modelos preditivos. Fatores externos e outras características (volume, indicadores técnicos, notícias, eventos macroeconômicos) que influenciam os preços das ações não foram incluídos, o que limita a capacidade preditiva dos modelos.<br>
4. <b>Período de Dados:</b> A análise e os modelos são baseados em um período de dados específico. O comportamento histórico pode não se repetir no futuro, e os modelos precisam ser reavaliados e retreinados periodicamente.<br>
5. <b>Divisão de Dados:</b> A divisão cronológica em treino, validação e teste é padrão, mas diferentes proporções ou técnicas de validação cruzada para séries temporais poderiam ser consideradas.<br>
6. <b>Natureza do Mercado:</b> O mercado de ações é inerentemente volátil e influenciado por inúmeros fatores imprevisíveis. Mesmo os modelos mais sofisticados não podem garantir previsões perfeitas. As previsões devem ser usadas como ferramentas de apoio, não como garantia de resultados.<br>
7. <b>Interpretabilidade do LSTM:</b> Embora o LSTM tenha apresentado bom desempenho preditivo, sua natureza de "caixa preta" torna a interpretação direta de como ele chega às previsões mais desafiadora em comparação com modelos mais tradicionais como o ARIMA.<br>

<h1><b>Próximos Passos e Melhorias na Modelagem:</b></h1><br>

1. <b>Otimização Mais Abrangente/Robusta do LSTM:</b> Retomar e concluir uma otimização de hiperparâmetros mais exaustiva para o modelo LSTM (expandindo a grade de busca ou utilizando técnicas como busca aleatória ou otimização Bayesiana) pode levar a um modelo ainda mais preciso.<br>
2. <b>Explorar Outros Modelos Avançados:</b> Experimentar outros modelos de séries temporais, como:<br>
   <b>SARIMA:</b> Se houver sazonalidade não capturada pelo ARIMA simples.<br>
   <b>Prophet:</b> Desenvolvido pelo Facebook, é robusto para dados com fortes efeitos sazonais e de feriados.<br>
   <b>Modelos de Machine Learning/Deep Learning Mais Complexos:</b> Redes neurais recorrentes (RNNs) mais profundas, LSTMs Bidirecionais, GRUs, ou até mesmo modelos baseados em Transformers (embora exijam mais dados e poder computacional).<br>
   <b>Modelos de Ensemble:</b> Combinar as previsões de diferentes modelos pode frequentemente levar a resultados mais robustos.<br>
3. <b>Inclusão de Features Adicionais (Engenharia de Atributos):</b> A previsão de preços de ações é complexa e não depende apenas do histórico de preços. Incluir outras features relevantes pode melhorar significativamente os modelos:<br>
   <b>Indicadores Técnicos:</b> Médias móveis de diferentes períodos (além da usada como baseline), RSI, MACD, bandas de Bollinger, etc.<br>
   <b>Volume de Negociação:</b> O volume pode indicar a força de um movimento de preço.<br>
   <b>Fatores Macroeconômicos:</b> Taxa de juros, inflação, dados de emprego, etc.<br>
   <b>Sentimento de Notícias/Redes Sociais:</b> Análise de sentimento de notícias relacionadas às empresas ou do sentimento geral do mercado.<br>
   <b>Preços de Outras Ações/Índices:</b> A correlação vista anteriormente sugere que os movimentos de ações correlacionadas são relevantes.<br>
4. **Previsões Multi-passos:</b> Em vez de prever apenas o próximo dia, explorar a previsão para múltiplos dias ou semanas no futuro. Isso é mais desafiador, mas mais útil para estratégias de investimento de médio prazo.<br>
5. **Considerar a Volatilidade:</b> Modelos que explicitamente modelam a volatilidade (como modelos GARCH) podem ser úteis para entender e prever a incerteza dos preços.<br>

<h2><b>Melhorias na Análise e Avaliação:</b></h2><br>

6. <b>Análise Mais Profunda de Resíduos:</b> Analisar os erros de previsão (resíduos) para identificar padrões não capturados pelos modelos.<br>
7. <b>Métricas de Avaliação Adicionais:</b> Considerar outras métricas relevantes para previsão de séries temporais, como MASE (Mean Absolute Scaled Error) ou diferentes tipos de erro percentual.<br>
8. <b>Backtesting:</b> Simular estratégias de negociação baseadas nas previsões para avaliar seu desempenho financeiro real no histórico de dados.<br>

<h2><b>Boas Práticas e Robustez:</b></h2><br>

9. <b>Validação Cruzada para Séries Temporais:</b> Implementar técnicas de validação cruzada apropriadas para dados de séries temporais (por exemplo, Time Series Split) para obter uma estimativa mais robusta do desempenho do modelo.<br>
10. <b>Tratamento de Outliers e Eventos Especiais:</b> Considerar o tratamento específico de outliers extremos ou o impacto de eventos de mercado (como a pandemia de COVID-19, que pode ter impactado os dados iniciais).<br>
