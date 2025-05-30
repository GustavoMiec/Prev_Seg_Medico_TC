# 💡 Previsão de Custos Médicos com Regressão e Interface Interativa

Este projeto tem como objetivo prever os **custos médicos individuais** com base em informações demográficas, estilo de vida e plano de saúde. Ele combina **modelos de regressão (Linear, Ridge, Random Forest)** com uma **interface interativa no Jupyter Notebook**, permitindo simulações personalizadas.

## 📊 Tecnologias Utilizadas

- Python 3.10+
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Statsmodels
- Widgets (`ipywidgets`)
- Jupyter Notebook

## ⚙️ Funcionalidades

- Carregamento e visualização de dados realistas de saúde
- Modelagem preditiva usando Regressão Linear, Ridge e Random Forest
- Validações estatísticas: VIF e Teste de Breusch-Pagan
- Interface interativa para simular previsões de custo com diferentes perfis
- Suporte a campos personalizados (ex: profissão, doenças familiares, prática de exercícios)

## 🧪 Variáveis Consideradas

- Idade
- Sexo
- IMC (Índice de Massa Corporal)
- Fumante
- Frequência de exercícios por semana
- Doenças familiares (cardíacas, diabetes, hipertensão)
- Renda mensal
- Tipo de plano de saúde
- Profissão

## 🚀 Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seuusuario/projeto-custos-medicos.git
   cd projeto-custos-medicos
   ```

2. Execute o Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Abra o notebook `modelo_interativo.ipynb` e execute as células.

## 🧠 Modelos Treinados

- **Regressão Linear** (baseline simples)
- **Ridge Regression** (regularização)
- **Random Forest Regressor** (melhor desempenho preditivo)

A performance dos modelos foi avaliada com métricas como RMSE e R².

## 📈 Exemplos de Uso

Com a interface interativa, é possível:

- Simular o custo médico para diferentes perfis
- Comparar como fatores como IMC, tabagismo ou doenças familiares afetam o custo
- Ajustar a profissão ou plano de saúde e ver impacto no valor previsto

## 📌 Observações

- Este projeto é educacional e usa dados simulados.
- As previsões não substituem avaliação médica real.

## 📚 Licença

Distribuído sob a licença MIT.
