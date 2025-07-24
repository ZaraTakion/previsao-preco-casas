# Previsão de Preços de Casas com Machine Learning

Este projeto de Ciência de Dados tem como objetivo prever o preço de venda de casas com base em diversas características, como tamanho, localização, número de cômodos, ano de construção, entre outras. O projeto foi desenvolvido com foco educacional e para ser incluído no portfólio profissional.

## Objetivo

O objetivo principal deste projeto é aplicar modelos de regressão supervisionada para prever o valor de venda (`SalePrice`) de imóveis residenciais a partir de um conjunto de dados históricos. As principais etapas do projeto incluem:

- Análise Exploratória de Dados (EDA)
- Limpeza e preparação dos dados
- Modelagem com algoritmos de Regressão
- Avaliação de desempenho dos modelos
- Visualização dos resultados

## Ferramentas e Tecnologias

- Python 3
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Dataset do Kaggle

## Estrutura do Projeto

```
housing-price-project/
│
├── data/               # Dados brutos (CSV)
├── notebooks/          # Notebooks com código e análises
├── outputs/            # Gráficos e previsões geradas
├── README.md           # Este arquivo
├── requirements.txt    # Bibliotecas utilizadas
└── .gitignore          # Arquivos ignorados pelo Git
```

## Modelos Utilizados

- Regressão Linear
- Árvore de Decisão
- Random Forest Regressor

## Resultados (métricas de avaliação)

| Modelo            | MAE (Erro Absoluto Médio) | RMSE (Erro Quadrático Médio) | R² (Coef. de Determinação) |
|-------------------|---------------------------|------------------------------|----------------------------|
| Regressão Linear  | _..._                     | _..._                        | _..._                      |
| Árvore de Decisão | _..._                     | _..._                        | _..._                      |
| Random Forest     | _..._                     | _..._                        | _..._                      |

> Preencha com os resultados reais obtidos nos testes.

## Visualizações

- Distribuição dos preços das casas
- Correlação entre variáveis
- Comparação entre valor real e previsto
- Distribuição dos erros absolutos

## Dataset

Fonte: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

## Conclusões

- O modelo Random Forest foi o que apresentou o melhor desempenho em termos de precisão.
- As previsões geradas são satisfatórias, com erro médio dentro de um limite aceitável.
- O projeto pode ser facilmente adaptado a outros conjuntos de dados do mercado imobiliário.

## Como rodar este projeto

1. Clone este repositório.
2. Acesse o notebook no Google Colab.
3. Baixe o dataset no [Kaggle](https://www.kaggle.com/).
4. Execute todas as células do notebook para realizar a análise e prever os preços das casas.

## Autor

- Zara Takion  
Desenvolvedor em formação, com foco em Ciência de Dados.  
Projeto criado para fins educacionais e portfólio profissional.
