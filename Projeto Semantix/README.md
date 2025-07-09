
# 🔋 Estimativa de Autonomia de Veículos Elétricos com Machine Learning

Este projeto tem como objetivo prever a autonomia (em quilômetros) de veículos elétricos com base em suas especificações técnicas e físicas, utilizando técnicas de aprendizado de máquina.

## 📌 Problema
Com a popularização dos veículos elétricos, prever a autonomia de um modelo se tornou um desafio técnico e comercial relevante. Uma estimativa precisa da autonomia pode auxiliar consumidores, fabricantes e gestores públicos no planejamento urbano e de infraestrutura de recarga.

## 📂 Fonte de Dados
- Dataset: [Electric Vehicle Specifications Dataset 2025 – Kaggle](https://www.kaggle.com/datasets/urvishahir/electric-vehicle-specifications-dataset-2025)
- Registros: 478 modelos de veículos elétricos
- Atributos: 19 colunas com características físicas e técnicas
- Variável alvo: `range_km`

## 🔍 Etapas do Projeto
1. **Importação de Bibliotecas e Leitura dos Dados**
2. **Análise Exploratória (EDA)**
3. **Pré-processamento de dados**
4. **Treinamento e Avaliação dos modelos**
5. **Visualização dos resultados**
6. **Conclusões**

## Modelos Utilizados
- Regressão Linear
- Ridge
- Lasso
- Random Forest
- Gradient Boosting
- AdaBoost
- Extra Trees
- SVR
- KNN

## Resultados
A regressão linear simples apresentou o menor RMSE (16.11), ligeiramente melhor que o Ridge (16.46).

## Visualizações
O projeto inclui gráficos de dispersão, mapas de calor, histogramas e gráficos de importância de variáveis.

## Conclusões
- A autonomia é fortemente influenciada pela capacidade da bateria e pela eficiência energética.
- O modelo pode ser usado para simular a autonomia de veículos futuros a partir de suas especificações.
