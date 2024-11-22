# Detecção de Transações Fraudulentas

Este repositório contém o estudo de caso 1 da disciplina de Ciência de Dados do Centro Universitário de Brasília - CEUB. O objetivo é aplicar técnicas de Machine Learning para prever se uma transação é fraudulenta ou não.

## Descrição do Problema

O estudo utiliza o conjunto de dados [Fraud Transaction Detection](https://www.kaggle.com/code/llabhishekll/fraud-transaction-detection/input) disponível no Kaggle. A tarefa é construir e avaliar modelos de aprendizado de máquina para a detecção de fraudes em transações financeiras.

## Etapas do Projeto

1. **Análise Exploratória de Dados (EDA)**  
   - Realização de análises gráficas e tabulares para entender as características do conjunto de dados.  
   - Visualizações para identificar padrões e possíveis correlações.

2. **Construção de Modelos de Previsão**  
   - Desenvolvimento de modelos utilizando os algoritmos:
     - K-Nearest Neighbors (KNN)
     - Árvore de Decisão
     - Regressão Logística  
   - Comparação dos resultados entre os modelos.

3. **Seleção de Features**  
   - Identificação das variáveis mais importantes para a detecção de fraudes.  
   - Interpretação dos resultados.

4. **Avaliação de Desempenho**  
   - Apresentação das métricas:
     - Matriz de confusão
     - Acurácia
     - Precisão
     - Recall  

5. **Ajustes e Otimização**  
   - Aplicação de melhorias para aumentar o desempenho dos modelos.  
   - Apresentação dos resultados após os ajustes.

## Arquivos no Repositório

- `Notebook_Modelo_Fraude.ipynb`: Notebook contendo todo o desenvolvimento do estudo, incluindo análise exploratória, construção dos modelos e avaliação dos resultados.
- `Trabalho1.pdf`: Descrição completa das instruções do estudo de caso.

## Conjunto de Dados

- O conjunto de dados pode ser acessado no [Kaggle](https://www.kaggle.com/code/llabhishekll/fraud-transaction-detection/input).  
  Certifique-se de baixar e carregar os dados antes de executar o notebook.

## Ferramentas e Tecnologias

- Python
- Pandas
- NumPy
- Matplotlib/Seaborn
- Scikit-learn
