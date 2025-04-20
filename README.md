
# Projeto de Criação Automatizada de Modelos Preditivos com Ajuste Fino de Hiperparâmetros<br><br>

## 📌 Visão Geral<br>
Este repositório demonstra como configurar e otimizar hiperparâmetros para cinco algoritmos fundamentais de Machine Learning:<br>

- Random Forest<br>

- SVM (Support Vector Machines)<br>

- KNN (K-Nearest Neighbors)<br>

- Naive Bayes<br>

- Regressão Logística<br><br>

O projeto automatiza a criação e avaliação de mais de 7.000 modelos preditivos, explorando combinações de hiperparâmetros para maximizar performance.
--------------------------------------------
## 🔍 O Que Você Vai Encontrar Aqui:
### 1. Configuração de Hiperparâmetros<br>
- Passo a passo para definir grades de parâmetros para cada algoritmo.<br>

- Exemplos práticos de como ajustar:<br>

- n_estimators, max_depth (Random Forest) <br>

- C, kernel (SVM)<br>

- n_neighbors, metric (KNN)<br>

- alpha (Naive Bayes)<br>

- penalty, C (Regressão Logística)<br>

### 2. Automação de Treinamento
- Uso do GridSearchCV e RandomizedSearchCV para buscar a melhor combinação de parâmetros.

- Processo automatizado que treina milhares de modelos e seleciona o melhor com base em métricas (acurácia, recall, F1-score).

### 3. Análise Comparativa
- Comparação de desempenho entre os 5 algoritmos.

- Trade-offs entre acuracia vs. tempo de treinamento.

- Discussão sobre interpretabilidade (por que Regressão Logística é mais explicável que Random Forest?).

### 4. Pré-processamento e Análise Exploratória
- Links para vídeos e materiais complementares sobre:

- Tratamento de dados faltantes (missing values).

- Análise de outliers.

- Visualizações (gráficos, distribuições).

- Normalização/Padronização.

## 🛠️ Como Usar Este Projeto: <br><br>
### Pré-requisitos<br>
- Python 3.8+

- Bibliotecas: scikit-learn, pandas, numpy, matplotlib, seaborn

## 📊 Resultados Destacados<BR><BR>
Algoritmo	Melhor Acurácia	Nº de Modelos Testados:<BR>
- Random Forest	78.64%	1080
- SVM	75.07%	1536
- KNN	74.14%	1144
- Naive Bayes	52.79%	12
- Regressão Logística	66.5%	2400<BR><BR>
## 📌 Principais Takeaways: <BR><BR>
- ✔ Random Forest teve o melhor desempenho, mas consome mais recursos computacionais.
- ✔ SVM e KNN são boas alternativas balanceando acurácia e eficiência.
- ✔ Naive Bayes foi rápido, mas menos preciso – ideal para baseline ou dados pequenos.
- ✔ Regressão Logística é mais interpretável, útil para casos onde explicação é crucial.

