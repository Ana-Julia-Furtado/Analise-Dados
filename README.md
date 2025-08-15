Análise de Dados de Salários na Área de Dados

Este repositório contém o passo a passo de uma análise de dados utilizando **Python**, **Pandas**, **Seaborn**, **Plotly** e **Streamlit**, com foco em entender padrões salariais no mercado de trabalho da área de dados.

Estrutura do Projeto

O projeto foi dividido em **módulos de aprendizado**:

### 🔹 Parte 1 – Análise Exploratória dos Dados (Pandas)
- Carregamento e inspeção inicial do dataset
- Verificação de linhas, colunas, tipos de dados e estatísticas descritivas
- Renomeação das colunas para português
- Análise de variáveis categóricas:
  - Senioridade (junior, pleno, senior, executivo)
  - Tipo de contrato (integral, parcial, contrato, freelancer)
  - Regime de trabalho (presencial, remoto, híbrido)
  - Tamanho da empresa (pequena, média, grande)

### 🔹 Parte 2 – Preparação e Limpeza dos Dados
- Identificação e tratamento de valores nulos (`NaN`)
- Estratégias de preenchimento:
  - Média, mediana, forward fill (`ffill`), backward fill (`bfill`)
  - Preenchimento com valores padrões
- Criação de `df_limpo` sem valores ausentes
- Conversão de colunas para tipos adequados (ex.: `ano` para inteiro)

### 🔹 Parte 3 – Visualização de Dados
- Criação de gráficos exploratórios:
  - Barras, histogramas e boxplots
  - Salário médio por senioridade
  - Distribuição de salários
  - Proporção de modelos de trabalho (remoto, presencial, híbrido)
  - Mapa coroplético de salários de **Data Scientists** por país
- Ferramentas usadas: **Matplotlib**, **Seaborn** e **Plotly**

### 🔹 Parte 4 – Construindo um Dashboard Interativo (Streamlit)
- Criação de dashboard para explorar:
  - Filtros dinâmicos (ano, senioridade, contrato, tamanho da empresa)
  - KPIs (média salarial, salário máximo, total de registros, cargo mais frequente)
  - Gráficos interativos (cargos, distribuição salarial, tipos de trabalho, mapa salarial por país)
- Deploy no **Streamlit Cloud**:  
👉 [Acesse o Dashboard Online]([https://eh455ewsyc8spgrzbcmkym.streamlit.app/])

---

## ⚙️ Tecnologias Utilizadas
- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Plotly](https://plotly.com/python/)
- [Streamlit](https://streamlit.io/)
- [PyCountry](https://pypi.org/project/pycountry/)

