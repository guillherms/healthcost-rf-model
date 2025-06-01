# Random Forest - Previsão de Custos Médicos

Este projeto utiliza um modelo de regressão baseado em **Random Forest** para prever os custos médicos individuais cobrados por planos de saúde, com base em atributos como idade, IMC, número de filhos, hábito de fumar, gênero e região.

## 📌 Objetivo

Desenvolver um modelo preditivo que estime com precisão os encargos médicos de um indivíduo, auxiliando seguradoras e profissionais da saúde na tomada de decisão baseada em dados.

## ⚙️ Tecnologias e Bibliotecas

- Python 3.10+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (opcional para EDA)

## 📁 Estrutura do Projeto


## 🧪 Pipeline do Projeto

1. **Importação e exploração dos dados**
2. **Tratamento e normalização dos dados**
3. **Engenharia de atributos**
4. **Divisão treino/teste**
5. **Treinamento com `RandomForestRegressor`**
6. **Avaliação do modelo (RMSE, R², etc.)**
7. **Interpretação das variáveis mais importantes**
8. **Predições com novos dados**

## 📊 Métricas de Avaliação

- **RMSE (Erro Quadrático Médio)**  
- **R² (Coeficiente de Determinação)**  
- Importância das variáveis explicativas

## 🔮 Exemplos de Uso

```python
# Prevendo o custo de um novo paciente
novo_paciente = {
    "idade": 45,
    "imc": 28.5,
    "filhos": 2,
    "fumante": 1,
    "gênero_masculino": 1,
    "região_sudeste": 1
}
modelo.predict([novo_paciente])
