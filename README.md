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
git clone https://github.com/EmmanoelB03/modeloCancerPulmonar.git
cd seurepositorio
```
2. Instale as dependências:

```bash
https://github.com/EmmanoelB03/modeloCancerPulmonar/blob/main/requirements.txt
pip install -r requirements.txt
```

3. Execute o notebook:

-Abra modeloTesteDeCancerPulmao.ipynb no Jupyter Notebook, Google Colab ou VS Code e execute célula por célula.

## 📊 Dataset

O conjunto de dados utilizado está disponível no Kaggle:

[Acesse o kaggle](https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer)


## 📌 Observações

-A classificação é feita com base em uma pequena quantidade de features, o que pode limitar a precisão do modelo.

-O modelo é meramente educacional e não deve ser utilizado para diagnósticos médicos reais.

## 📄 Licença - MIT

Este projeto está licenciado sob os termos da [Licença MIT](https://github.com/EmmanoelB03/modeloCancerPulmonar/blob/main/LICENSE)).

