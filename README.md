# Previsão de Doenças Cardíacas com Modelos de Classificação

## 📌 Sobre o Projeto
Este projeto tem como objetivo prever a presença de doenças cardíacas em pacientes utilizando modelos de classificação. O uso de dados médicos para prever doenças cardíacas permite uma tomada de decisão mais precisa e informada, além de contribuir para intervenções preventivas eficazes e personalizadas.

## 🎯 Objetivos
- Construir e avaliar modelos de classificação para prever a presença de doenças cardíacas.
- Obter métricas de desempenho como precisão, sensibilidade, especificidade e F1-Score.
- Identificar os atributos mais relevantes para a previsão da doença.
- Demonstrar a capacidade de generalização dos modelos por meio de validação cruzada.

## 🏗 Etapas do Projeto
1. **Análise Exploratória dos Dados (EDA):** Estudo inicial para entender a distribuição dos atributos e suas relações com o alvo (presença de doença cardíaca).
2. **Pré-processamento dos Dados:** Normalização ou padronização dos atributos contínuos, tratamento de valores ausentes e conversão de variáveis categóricas para representação numérica.
3. **Treinamento dos Modelos:** Aplicação de algoritmos de classificação e ajuste de hiperparâmetros.
4. **Avaliação e Interpretação:** Análise das métricas de desempenho e identificação das variáveis mais influentes.

## 📂 Estrutura do Repositório
```
📂 previsao-doencas-cardiacas
│── 📜 README.md              # Documentação do projeto
│── 📜 requirements.txt       # Dependências do projeto
│── 📂 data/                  # Conjunto de dados
    ├── preprocessed_data.csv  # Base de dados processada para EDA
│── 📂 notebooks/             # Notebooks para análise
│   ├── 📜 classificacao_doenca_cardiaca.ipynb     # Notebook único do projeto
```

## 🛠 Tecnologias Utilizadas
- **Linguagem:** Python 🐍
- **Bibliotecas:**
  - `pandas` para manipulação de dados
  - `numpy` para operações numéricas
  - `matplotlib/seaborn` para visualização dos resultados
  - `scikit-learn` para implementação dos modelos de machine learning
  - `imblearn` para tratamento de desbalanceamento de classes
  - `time` para medições de tempo

### 🔍 Modelos Utilizados
- **Árvores de Decisão (DecisionTreeClassifier)**
- **Floresta Aleatória (RandomForestClassifier)**
- **Regressão Logística (LogisticRegression)**
- **Máquinas de Vetores de Suporte (SVC)**
- **K-Nearest Neighbors (KNeighborsClassifier)**
- **Naïve Bayes (GaussianNB)**
- **Gradient Boosting (GradientBoostingClassifier)**
- **AdaBoost (AdaBoostClassifier)**
- **Bagging (BaggingClassifier)**
- **Redes Neurais Artificiais (MLPClassifier)**

## 📊 Fonte dos Dados
Os dados utilizados no projeto são provenientes do [UCI Machine Learning Repository - Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease), um conjunto de dados amplamente utilizado para pesquisas médicas relacionadas a doenças cardíacas.

