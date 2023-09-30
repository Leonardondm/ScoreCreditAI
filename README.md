# Projeto Python IA: Inteligência Artificial e Previsões

## Case: Score de Crédito dos Clientes
Você foi contratado por um banco para desenvolver um sistema que avalia o score de crédito dos clientes. O objetivo é analisar o perfil de todos os clientes do banco e, com base nessa análise, criar um modelo de inteligência artificial capaz de classificar automaticamente o score de crédito dos clientes em três categorias: Poor, Standard e Good.

### Visão Geral
Este repositório contém o código fonte e os dados necessários para desenvolver e treinar um modelo de classificação de score de crédito dos clientes. O projeto é dividido em várias etapas, cada uma representada por um notebook Jupyter:

### Importação e Análise dos Dados
No primeiro notebook, importamos os dados dos clientes a partir de um arquivo CSV e realizamos uma análise exploratória para entender a estrutura e os padrões dos dados. Isso inclui a verificação de valores faltantes e a codificação de variáveis categóricas em formato numérico.

### Preparação dos Dados
Neste notebook, preparamos os dados para treinamento do modelo. Separamos as variáveis de entrada (features) das variáveis de saída (target). Também dividimos o conjunto de dados em conjuntos de treinamento e teste para avaliar o desempenho do modelo.

### Treinamento do Modelo
Utilizamos três algoritmos de aprendizado de máquina para treinar modelos de classificação: Random Forest, K-Nearest Neighbors (KNN) e Redes Neurais Artificiais (RNA). Cada modelo é treinado e avaliado quanto à sua acurácia.

### Avaliação do Modelo
Neste notebook, avaliamos o desempenho dos modelos treinados usando métricas de avaliação, como a acurácia. Comparamos os resultados dos diferentes modelos para determinar qual deles é mais adequado para o problema em questão.

### Previsões em Novos Clientes
Finalmente, aplicamos o modelo escolhido para fazer previsões sobre o score de crédito de novos clientes. Os resultados são apresentados como uma classificação de Ruim, Ok ou Bom.

### Importância das Características
Investigamos a importância das características (variáveis) usadas pelo modelo para determinar o score de crédito. Isso ajuda a entender quais fatores têm maior impacto na decisão do modelo.

## Requisitos

Certifique-se de ter as seguintes bibliotecas Python instaladas em seu ambiente antes de executar o código:

- pandas
- scikit-learn
- numpy


Você pode instalá-las usando o pip:
```
pip install pandas scikit-learn numpy
```

## Como Usar
1. Clone este repositório em sua máquina local.
2. Certifique-se de que os arquivos `clientes.csv` e `novos_clientes.csv` estejam na mesma pasta que os notebooks.
3. Execute cada notebook na ordem numerada para seguir o fluxo do projeto.
4. Analise os resultados e utilize o modelo treinado para fazer previsões sobre novos clientes.

## Conclusão
Este projeto demonstra a aplicação de técnicas de aprendizado de máquina para resolver um problema real de classificação de score de crédito de clientes. O modelo treinado pode ser usado pelo banco para automatizar essa tarefa e tomar decisões mais informadas sobre concessão de crédito.

## Autor
Leonardo Nascimento Dias