SME0828 — Trabalho Final

Este repositório reúne o **Trabalho Final da disciplina SME0828 – Introdução à Ciência de Dados**, organizado em três notebooks principais que abordam desde a exploração inicial dos dados até a modelagem preditiva. O conjunto de dados utilizado é o famoso **Abalone Dataset**, cujo objetivo envolve analisar características físicas dos abalones e construir modelos capazes de predizer sua categoria etária (adulto ou infante) ou estimar sua idade aproximada.

---

## Estrutura do Repositório

O projeto está dividido em três notebooks, cada um com uma etapa distinta da análise:

### 1. **ICD_Visualização.ipynb**

Notebook dedicado à **exploração e visualização dos dados**.
Aqui são realizadas:

* análise descritiva das variáveis,
* gráficos exploratórios,
* investigação de padrões e possíveis relações entre atributos físicos (peso, diâmetro, altura etc.) e a idade dos abalones.


### 2. **ICD_Regressões_.ipynb**

Notebook focado nos **modelos de regressão**, incluindo:

* preparação dos dados,
* seleção de variáveis,
* ajuste de modelos de regressão para estimar o número de anéis (proxy de idade),
* avaliação de desempenho dos modelos.


### 3. **ICD_Reg_Logistica_.ipynb**

Notebook dedicado à **classificação binária** dos abalones entre *adultos* e *infantes*.
Contém:

* criação da variável binária,
* ajuste de modelos de Regressão Logística e Random Forest,
* busca de hiperparâmetros via GridSearchCV,
* avaliação final dos modelos.

---

## Objetivo Geral do Trabalho

O trabalho tem como propósito aplicar técnicas básicas de **ciência de dados e aprendizado de máquina**, passando por:

* limpeza e transformação dos dados,
* análise exploratória,
* modelagem preditiva,
* avaliação de desempenho,
* interpretação dos resultados obtidos.

Além disso, buscou-se investigar se atributos físicos simples seriam suficientes para prever a idade ou estágio reprodutivo dos abalones sem a necessidade de medições invasivas.

