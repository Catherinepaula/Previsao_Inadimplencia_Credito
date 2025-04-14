
# Projeto: Previsão de Inadimplência de Crédito

Este projeto tem como objetivo prever a inadimplência de crédito de clientes com base em suas características demográficas e comportamentais. O modelo utiliza dados de clientes para identificar padrões e prever a possibilidade de inadimplência, permitindo ações preventivas de concessão de crédito.

## 1. Coleta de Dados

Os dados utilizados neste projeto foram extraídos de um conjunto de informações de clientes que incluem características como idade, dependentes, histórico de relacionamento com a instituição financeira, entre outras.

## 2. Análise Exploratória de Dados

A análise exploratória é uma etapa essencial para entender a distribuição e correlação das variáveis. Utilizamos gráficos de dispersão, histogramas e um mapa de calor para verificar a relação entre as variáveis preditivas e a variável alvo, 'default', que indica se o cliente foi inadimplente.

## 3. Pré-processamento

Antes de aplicar os modelos de aprendizado de máquina, os dados foram preparados por meio dos seguintes passos:
- Separação entre as variáveis preditivas e a variável alvo.
- Padronização das variáveis numéricas utilizando o `StandardScaler`.

## 4. Modelagem

Foi utilizado o modelo **Árvore de Decisão** para classificar os clientes com base nas variáveis preditivas. O modelo foi treinado e avaliado usando a matriz de confusão e o relatório de classificação.

## 5. Resultados

Os resultados foram avaliados com as métricas de **precisão**, **recall** e **F1-score**, permitindo uma análise detalhada do desempenho do modelo.

## 6. Conclusão

O modelo de aprendizado de máquina foi capaz de prever com razoável precisão os clientes inadimplentes, fornecendo insights valiosos para a tomada de decisão na concessão de crédito.

---

### Como Rodar o Projeto

1. Clone este repositório.
2. Coloque o arquivo `dados_credito.csv` no mesmo diretório que o notebook.
3. Execute o notebook `Previsao_inadimplencia_credito.ipynb` para gerar as previsões.
