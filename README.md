# Análise de Ativos Financeiros

Este projeto tem como objetivo realizar uma análise quantitativa e comparativa entre ativos brasileiros e internacionais, utilizando métricas clássicas de mercado para avaliação de risco e retorno.

---

# Objetivo

Avaliar o comportamento de diferentes ativos financeiros sob a ótica de:

* Retorno esperado
* Volatilidade
* Sharpe Ratio
* Drawdown máximo
* Correlação entre ativos

A proposta é identificar quais ativos apresentam melhor relação risco-retorno e como se comportam em conjunto em um portfólio.

---

## 📌 Ativos Analisados

* **PETR4.SA** — Petrobras (Brasil)
* **BBDC4.SA** — Bradesco (Brasil)
* **SPY** — S&P 500 ETF (EUA)
* **TLT** — Treasury Bonds ETF (EUA)

👉 A escolha combina ativos de:

* renda variável brasileira
* mercado internacional
* renda fixa americana

---

# Metodologia

A análise foi realizada em Python utilizando dados históricos do Yahoo Finance.

### 🔹 Coleta de dados

* Preços de fechamento (`Close`)
* Período: 2025 até o presente

### 🔹 Cálculo dos retornos

* Retornos simples (`pct_change`)
* Retornos logarítmicos:



# Métricas utilizadas

* **Retorno médio anualizado**
* **Volatilidade anualizada**
* **Sharpe Ratio**
* **Drawdown máximo**
* **Matriz de correlação**

---

# Resultados

Os resultados são organizados em tabela (`Resultados.csv`) contendo:

* Retorno médio (%)
* Volatilidade (%)
* Sharpe Ratio
* Drawdown máximo (%)

Os ativos são ordenados pelo Sharpe Ratio, permitindo identificar a melhor eficiência risco-retorno

# Principais Insights

* Ativos brasileiros tendem a apresentar **maior volatilidade e maior potencial de retorno**
* Ativos internacionais mostram **menor risco e maior estabilidade**
* A diversificação entre mercados reduz o risco total do portfólio
* O Sharpe Ratio permite identificar ativos mais eficientes, não apenas mais rentáveis

---

# Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* yFinance

# Possíveis Extensões

* Otimização de portfólio (Markowitz)
* Fronteira eficiente
* Backtesting de estratégias
* Inclusão de mais ativos e classes

---

# Conclusão

A análise evidência a importância de avaliar ativos não apenas pelo retorno, mas pela relação risco-retorno.

A utilização de métricas como Sharpe Ratio e drawdown permite uma visão mais robusta da qualidade dos investimentos, especialmente em um contexto de diversificação internacional.

---

# Autor

Bruno da Silva Agostinho
Estudante de Física — USP
Interesse em mercado financeiro e análise quantitativa
