# Titanic Survival Prediction with Random Forest

Este repositório contém um modelo de aprendizado de máquina desenvolvido para prever a sobrevivência dos passageiros do Titanic, utilizando dados do famoso conjunto de dados do Kaggle. O projeto foca no uso de Random Forest como classificador e inclui etapas básicas de análise de dados e pré-processamento.

## Principais características
- Carregamento e análise inicial dos dados de treino e teste.
- Implementação de um modelo `RandomForestClassifier` da biblioteca `sklearn`.
- Configuração dos parâmetros do modelo para otimizar o desempenho.
- Utilização de abordagens simples, como escolhas majoritárias, para lidar com valores ausentes ou categóricos.

## Tecnologias utilizadas
- `pandas` para manipulação de dados.
- `numpy` para cálculos matemáticos.
- `scikit-learn` para o desenvolvimento do modelo de aprendizado de máquina.

## Como usar
1. Clone este repositório.
2. Certifique-se de que os arquivos `train.csv` e `test.csv` estão disponíveis na mesma pasta do notebook.
3. Execute o notebook para treinar o modelo e gerar as previsões.

## Resultados
- O modelo obteve um score de 0.76 no Kaggle.

## Próximos passos
- Experimentar outros classificadores..
- Implementar validação cruzada para melhorar a generalização.
- Melhorar o desempenho do modelo para aumentar o score no Kaggle.
