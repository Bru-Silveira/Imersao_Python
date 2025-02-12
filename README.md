# 📊 Imersão Python - Do Excel à Análise de Dados

Este repositório contém materiais e anotações da imersão "Python - Do Excel à Análise de Dados" promovida pela Alura. A imersão incluiu 5 aulas focadas na análise e manipulação de dados utilizando Google Sheets e Python.

## 📌 Conteúdo das Aulas

### 📈 Aula 1 - Análise Exploratória com Google Sheets
Análise e manipulação de dados utilizando uma planilha da Bolsa de Valores do Brasil (B3) no Google Sheets. Foram exploradas fórmulas e expressões similares ao Excel, como:
- Porcentagem, soma, divisão, multiplicação
- PROCV/VLOOKUP
- IF/SE

### 📊 Aula 2 e 3 - Gráficos e Análises com Google Colab e Pandas
Utilização do Python no Google Colab para refazer manipulações feitas no Google Sheets, utilizando a biblioteca Pandas:
- Importação de dados do Google Sheets/Excel (método `read`)
- Armazenamento em DataFrames
- Manipulação de tabelas com `copy`, `rename`, `drop`
- Combinação de DataFrames com `merge`
- Formatação de valores float com `options.display.float_format`
- Uso de `lambda` e `apply` para operações condicionais
- Agrupamento de dados com `groupby` e `sum`
- Criação de gráficos interativos com `plotly.express` (`px.bar`)

### 📉 Aula 4 - Análises Avançadas de Ações e Gráficos de Velas
Exploração de bibliotecas para visualização de dados financeiros:
- `matplotlib`, `yfinance`, `plotly.graph_objects` e `plotly.subplots`
- Gráficos de velas (candlestick)
- Visualizações interativas para análise de tendências

### 🔮 Aula 5 - Previsão de Séries Temporais de Ações
Utilização da biblioteca Prophet para previsão automática de séries temporais:
- Modelagem de tendências e padrões sazonais
- Tratamento de feriados, lacunas nos dados e mudanças abruptas

## 🛠️ Tecnologias Utilizadas
- Google Sheets
- Python (Google Colab e VS Code)
- Pandas
- Plotly
- Matplotlib
- yFinance
- Prophet

## 🚀 Como Usar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install pandas plotly matplotlib yfinance prophet
   ```
3. Execute os notebooks no Jupyter Notebook ou Google Colab.

## 📩 Contato
Caso tenha dúvidas ou sugestões, sinta-se à vontade para entrar em contato ou abrir uma issue neste repositório.

---
Este projeto foi desenvolvido durante a Imersão Python promovida pela [Alura](https://www.alura.com.br/).

