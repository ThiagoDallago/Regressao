# Regressão
Estudos sobre aprendizado supervisionado - problemas de regressão.

O presente projeto tem por objetivo a aplicação de modelo de Regressão para prever o preço de venda de casas. 
O dataset conta com 79 variáveis ​​explicativas descrevendo (quase) todos os aspectos dos imóveis residenciais em Ames, Iowa.

Objetivo de negócio: Ajudar construtoras, imobiliárias, compradores, corretores e investidores a estimarem corretamente o valor de um imóvel com base em dados históricos. Isso pode:
**Otimizar o preço de venda, maximizando o lucro e reduzindo o tempo no mercado.
**Evitar subavaliação ou superavaliação de imóveis.
**Auxiliar bancos na avaliação de garantias de crédito imobiliário.
**Automatizar processos em plataformas digitais de venda e aluguel de imóveis.

Na análise de dados verificamos:
- Análise estatística
- Distribuição dos preços de venda
- Quais variáveis possuem maior correlação com SalePrice?
- Top 10 bairos mais valorizados
- Existe sazonalidade nas vendas?
- Qual o preço médio por mês
- Quais foram os bairros que mais venderam nos meses de Maio a Junho?

Na preparação dos dados foram aplicadas as seguintes técnicas:
1 - Gerar Metadados da ABT (Tabela Analítica de Modelagem);

2 - Tratamento de missing (nulos);

3 - Tratamento de categóricas de alta cardinalidade (LabelEncoder);

4 - Tratamento de categóricas de baixa cardinalidade (OneHotEncoder);

5 - Aplicar normalização a toda tabela de modelagem (ABT);

5 - Gerar artefatos para implantação do data prep realizado.

No processo de modelagem

a) foi feito o treinamento de três modelos diferentes
  - GradientBoostingRegressor
  - lightgbm
  - RandomForestRegressor
    
b) O desempenho do modelo foi medido pelo R².

c)  Ajuste dos hiperparâmetros usando validação cruzada.
