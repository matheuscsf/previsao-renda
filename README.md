# Previsão de Renda com Modelos de Machine Learning

## Sobre o Projeto
Este projeto utiliza técnicas de Data Science e Machine Learning para prever a renda mensal de indivíduos com base em características pessoais e econômicas. O modelo foi desenvolvido utilizando o framework CRISP-DM, com foco em análise de dados, construção de modelos preditivos e criação de uma aplicação interativa em Streamlit.

## Objetivo
O objetivo principal é construir e avaliar modelos preditivos para prever a variável renda, além de apresentar os resultados de forma interativa para visualização e análise de desempenho

## Estrutura do Projeto

### 1. Exploração e Análise de Dados

Realizamos uma análise exploratória completa para entender as distribuições e relações entre as variáveis. Destaques:

Histogramas, Scatter Plots e Box Plots das principais variáveis.

Tratamento de valores ausentes e remoção de outliers.

Construção de variáveis como:

faixa_etaria (categorias de idade)

tempo_emprego_categoria (faixas de tempo de emprego)


proporcao_filhos_residencia (proporção de filhos por residência).

### 2. Modelagem
Modelos de Machine Learning foram treinados e avaliados:

Regressão Linear: Utilizado como baseline.
Random Forest Regressor: Melhor desempenho.
Gradient Boosting Regressor: Avaliado para comparação.
As métricas utilizadas incluem:

R² (Coeficiente de Determinação)

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

### 3. Aplicação Interativa
Foi desenvolvida uma aplicação em Streamlit para visualização dos resultados:

Gráficos interativos (Scatter Plots, Histogramas).

Importância das variáveis no modelo Random Forest.

Matriz de erro para comparar variáveis.

## Tecnologias Utilizadas
Linguagem de Programação: Python

Bibliotecas:

Análise de Dados: Pandas, NumPy

Visualização: Matplotlib, Seaborn

Modelagem: Scikit-learn

Interface Interativa: Streamlit

Machine Learning: Random Forest, Gradient Boosting

## Resultados
Modelo Selecionado: Random Forest Regressor

R²: 0.403

RMSE: 0.792

MAE: 0.522

O Random Forest apresentou o melhor desempenho e foi implantado na aplicação interativa.

##Como Executar o Projeto

### 1. Pré-requisitos:
Certifique-se de ter instalado:

Python 3.7+

Pipenv ou virtualenv (opcional)

# Estrutura do Repositório

📂 previsao-renda/

├── 📁 data/              # Dados utilizados no projeto

├── 📁 notebooks/         # Jupyter Notebooks com análises exploratórias

├── 📂 app.py             # Código da aplicação Streamlit

├── 📂 model/             # Modelos treinados salvos

└── 📂 README.md          # Arquivo descritivo do projeto

# Demonstração
[7b7d55b3-9b9a-4027-b983-c42111494f8d.webm](https://github.com/user-attachments/assets/dc6f53b4-79a2-4448-a6ed-523c428c303b)
