# Previsão de Score de Crédito usando Machine Learning 🤖

Este projeto utiliza técnicas de machine learning para prever o score de crédito de clientes, com base em um conjunto de dados que contém diversas informações relevantes. O objetivo principal é treinar modelos capazes de prever o score de crédito e identificar quais características são mais importantes para essa previsão.

## Descrição do Projeto

Neste projeto, foi usada uma base de dados de clientes com diversas características (como profissão, renda, etc.), e o foco foi prever o score de crédito desses clientes. Utilizamos dois modelos de machine learning para fazer as previsões:

- **Random Forest Classifier**: Um modelo baseado em árvores de decisão.
- **K-Nearest Neighbors (KNN)**: Um modelo baseado nos vizinhos mais próximos.

Além disso, exploramos as variáveis mais importantes para definir o score de crédito dos clientes.

### Funcionalidades

- Leitura e tratamento de dados usando **Pandas**.
- Codificação de variáveis categóricas utilizando **LabelEncoder**.
- Treinamento de dois modelos de machine learning:
  - Random Forest
  - K-Nearest Neighbors
- Avaliação da performance dos modelos com base na **acurácia**.
- Previsão de scores de crédito para novos clientes.
- Identificação das características mais importantes para a previsão do score de crédito usando o **Random Forest**.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Pandas**: Manipulação de dados.
- **Scikit-learn**: Biblioteca para machine learning.
- **IPython.display**: Para exibir tabelas de forma interativa.
- **RandomForestClassifier** e **KNeighborsClassifier**: Modelos de machine learning utilizados para o treinamento e previsão.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/BrunoH4ds/credito-previsoes.git
2. Instale as dependências necessárias:
    ```bash
    pip install pandas scikit-learn
    pip install ipython
3. Adicione os arquivos clientes.csv e novos_clientes.csv na pasta correspondente.

4. Execute o script main.py ou rode o código diretamente em um Jupyter Notebook.

## Estrutura do Código

- Importação e Leitura dos Dados: Os dados dos clientes são carregados e exibidos usando Pandas.
- Tratamento de Dados: Variáveis categóricas são convertidas em valores numéricos com LabelEncoder, facilitando o uso em algoritmos de machine learning.
- Divisão do Dataset: O dataset é dividido em dados de treino e teste usando train_test_split.
- Treinamento dos Modelos: Dois modelos são treinados: Random Forest e KNN.
- Avaliação: A acurácia dos modelos é avaliada e comparada.
- Previsões Finais: Novos dados de clientes são fornecidos para que o modelo faça previsões.
- Análise de Importância: Identificação das características mais relevantes para a previsão do score de crédito.

##Resultados

Os modelos foram avaliados com base na acurácia, e as previsões foram comparadas com os valores reais de teste. Também foi calculada a importância das variáveis para o modelo de Random Forest, permitindo uma melhor compreensão das características que mais influenciam o score de crédito.
