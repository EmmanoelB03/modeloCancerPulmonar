# 🫁 Modelo de Predição de Câncer de Pulmão

Este projeto tem como objetivo analisar dados de pacientes e aplicar técnicas de aprendizado de máquina para prever a presença de câncer de pulmão com base em variáveis como idade, histórico de tabagismo, dores no peito e ansiedade.

## 📁 Sobre o Projeto

O notebook realiza as seguintes etapas:

- **Coleta de dados**: download do dataset [Lung Cancer Survey](https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer) via `kagglehub`.
- **Pré-processamento e limpeza**:
  - Conversão de variáveis categóricas para numéricas.
  - Normalização da idade com `StandardScaler`.
  - Identificação e remoção de outliers.
- **Visualizações**:
  - Gráficos de dispersão para análise exploratória.
  - Visualização de clusters após agrupamento.
- **Modelagem**:
  - Algoritmo de agrupamento KMeans aplicado para segmentar os dados.
  - Classificação utilizando Random Forest.

## 🧪 Tecnologias utilizadas

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- KaggleHub (para download do dataset)

## 🚀 Como executar

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/seurepositorio.git
cd seurepositorio
