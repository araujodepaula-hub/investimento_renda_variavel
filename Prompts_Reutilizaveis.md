Para apoiar futuras revisões e garantir que este notebook permaneça atualizado e tecnicamente rigoroso, sugiro o seguinte conjunto de **prompts reutilizáveis**. Eles foram estruturados com base nas metodologias de análise (Markowitz, Sharpe) e no cenário macroeconômico (2026) detalhados nas fontes.

### 1\. Atualização de Cenário Macroeconômico e Projeções

*Use este prompt para revisar se as premissas de juros e inflação ainda refletem a realidade do mercado.*  
"Com base nos dados mais recentes do Banco Central, atualize as projeções para 2026\. A **Taxa Selic** permanece em **15,00%** ou houve alteração na postura restritiva? 1, 2\. Revise também se a projeção do **PIB (2,5%)** e do **IPCA** ainda servem como base sólida para calcular o custo de oportunidade e a **taxa livre de risco** no modelo de Sharpe 3-5."

### 2\. Rebalanceamento e Eficiência de Portfólio (Teoria de Markowitz)

*Use este prompt para auditar a composição da carteira e a correlação entre os ativos.*  
"Analise a matriz de **correlação e covariância** atual dos ativos 6, 7\. Identifique se houve aumento na correlação entre classes distintas, o que poderia comprometer a redução do **risco não-sistemático** 8, 9\. Recomende um **rebalanceamento** para retornar à **Fronteira Eficiente**, vendendo ativos que valorizaram excessivamente e comprando aqueles que mantêm fundamentos sólidos, mas estão abaixo do peso alvo 4, 10."

### 3\. Auditoria de Valuation e Prêmios de Risco

*Use este prompt para verificar se o retorno das empresas ainda justifica o risco em juros altos.*  
"Dado o cenário de juros elevados, revise o **Equity Risk Premium (ERP)** das ações selecionadas 11\. O **ROIC** e a eficiência operacional das empresas ainda superam o **WACC** (Custo Médio Ponderado de Capital) atualizado? 11, 12\. Utilize o modelo de **Fluxo de Caixa Descontado (DCF)** para verificar se a sensibilidade à taxa de desconto de 15% exige uma projeção mais conservadora de crescimento 13."

### 4\. Verificação de Conformidade Tributária e Custos

*Use este prompt para garantir que as regras de impostos e isenções não mudaram.*  
"Revise as regras de **tributação para 2026**. A isenção para vendas de ações até **R$ 20.000,00** por mês ainda está vigente para pessoas físicas? 14, 15\. Verifique se houve mudanças nas alíquotas para **FIIs (20%)** ou no tratamento de **dividendos** e **JCP** 16-18. Atualize os custos de corretagem e taxas da B3 para garantir que o cálculo de rentabilidade líquida no Python esteja correto 15."

### 5\. Refinamento Técnico do Código Python

*Use este prompt para otimizar as bibliotecas e a coleta de dados automatizada.*  
"Verifique a estabilidade da conexão com a API do **Yahoo Finance (yfinance)** ou **Pandas DataReader** 19, 20\. O código atual para calcular o **Índice de Sharpe** e o **CAPM** está tratando corretamente valores nulos ou feriados (dropna)? 21, 22\. Sugira a implementação de bibliotecas adicionais como **SciPy** para otimização matemática mais avançada da Fronteira Eficiente 23, 24."

### 6\. Monitoramento de Vieses Comportamentais

*Use este prompt para uma autoavaliação da tomada de decisão.*  
"Revise as últimas decisões de compra e venda à luz das **Finanças Comportamentais** 25\. Houve influência do **efeito manada** ou de **aversão à perda** ao manter posições perdedoras na esperança de 'empatar'? 25\. Reafirme o plano de investimento de **longo prazo** (superior a 5 anos) para ignorar ruídos de volatilidade de curto prazo 26, 27."  
