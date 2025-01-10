# EBAC-Projeto-Python-Curso-Cientista-de-Dados
Notebook Projeto Phyton Cientista de Dados - EBAC


# Introdução

Este projeto apresenta uma análise de crédito com base em uma base de dados fictícia, desenvolvida pelo Professor André Perez da EBAC. A concessão de crédito é um processo complexo que envolve múltiplas variáveis, sendo essencial desenvolver uma estratégia eficiente para segmentar clientes, evitando a perda de bons pagadores e o aumento da inadimplência. Neste projeto, realizamos etapas de processamento de dados, incluindo limpeza, engenharia de recursos e visualização de variáveis da base.

# Objetivo

O objetivo deste projeto é realizar uma análise exploratória e visualização dos dados para entender as relações entre as variáveis financeiras e demográficas. Utilizamos ferramentas como pandas, matplotlib e seaborn para explorar e visualizar os dados, identificando padrões e insights que podem ajudar na segmentação de clientes e na concessão de crédito.

# Processamento e Limpeza dos Dados

Os dados foram carregados e limpos para garantir consistência. Durante o processo de limpeza, tratamos valores ausentes e convertemos variáveis financeiras de string para tipo numérico. Para as colunas com valores nulos, aplicamos técnicas como preenchimento com a média dos valores ou o método de "forward fill". As variáveis categóricas foram tratadas e analisadas para melhor compreensão das distribuições.

# Visualizações e Análises

Realizamos diversas análises para entender melhor os dados e identificar padrões relevantes:

- **Distribuição de Idades**: A maioria dos clientes está na faixa etária de 30-40 anos.
- **Relação entre Estado Civil e Salário Anual**: Identificamos que pessoas casadas tendem a ter um salário anual médio mais alto.
- **Relação entre Meses de Relacionamento e Salário Anual**: Clientes com mais tempo de relacionamento com a instituição tendem a ter um salário maior.
- **Correlação entre Variáveis Numéricas**: Exploramos a relação entre variáveis como salário anual, meses de relacionamento e limite de crédito.

# Conclusões

- **Segmentação por Faixa Etária**: A segmentação por faixa etária é útil para campanhas de marketing direcionadas.
- **Clientes Fiéis**: Clientes com mais de 40 meses de relacionamento possuem um comportamento mais fiel, sendo um público ideal para ofertas personalizadas.
- **Cartões "Gold"**: Clientes que possuem cartões do tipo "gold" possuem maiores salários anuais e maior tempo de relacionamento.

# Recomendações

- Desenvolver campanhas segmentadas por faixa etária e tipo de cartão.
- Oferecer benefícios para clientes com mais de 40 meses de relacionamento.
- Realizar mais análises para entender padrões de inadimplência e prever riscos.

# Bibliotecas Utilizadas

- **pandas**: Para manipulação e análise de dados.
- **seaborn**: Para visualização gráfica dos dados.
- **matplotlib**: Para criação de gráficos e ajustes visuais.
- **numpy**: Para operações numéricas.

