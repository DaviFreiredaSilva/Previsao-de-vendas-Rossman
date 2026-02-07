# Previsão de Vendas da Rossmann com Redes Neurais

## Visão Geral

Este projeto tem como objetivo prever **vendas diárias das lojas da rede Rossmann** utilizando **Redes Neurais**, com comparação com um modelo de Regressão Linear**.

## Destaques do Projeto

* Comparação entre modelo clássico e Deep Learning
* Pré‑processamento robusto (normalização e encoding)
* Problema real de negócio (forecasting no varejo)

## Dataset

O conjunto de dados utilizado é o **Rossmann Store Sales**, disponível no Kaggle.

Principais tipos de variáveis:

* Informações da loja
* Datas
* Promoções
* Feriados
* Vendas históricas

## Modelos Utilizados

### Regressão Linear

Utilizada como referência para avaliar se o uso de Deep Learning gera ganho real de desempenho.

### Rede Neural

Modelo de regressão com múltiplas camadas densas, treinado após:

* Normalização de variáveis numéricas
* One-Hot Encoding de variáveis categóricas
* Separação entre conjuntos de treino e teste

O objetivo é capturar **relações não lineares** presentes nos dados de vendas.

---

## Habilidades Demonstradas

* Machine Learning supervisionado (regressão)
* Deep Learning aplicado a dados tabulares
* Feature engineering
* Avaliação e comparação de modelos
* Pensamento orientado a negócio

---

## Tecnologias e Bibliotecas

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## Pipeline de Machine Learning

1. Carregamento dos dados
2. Limpeza e preparação
3. Engenharia de features
4. Padronização e codificação
5. Treinamento dos modelos
6. Avaliação e comparação de desempenho

---

## Avaliação

Os modelos são avaliados com métricas de erro para regressão, permitindo uma comparação objetiva entre o baseline e a Rede Neural.

> **Observação:** As métricas detalhadas (ex: RMSE, MAE) e gráficos de desempenho estão documentados diretamente no notebook.

---

## 🔗 Links

* Notebook no Kaggle: *(adicionar link)*
* Dataset: Rossmann Store Sales (Kaggle)

---

## 🚀 Como Executar o Projeto

1. Clone este repositório
2. Instale as dependências necessárias
3. Execute o notebook `modelo-de-redes-neurais-analise-rossmann.ipynb`

O projeto foi originalmente desenvolvido e executado no **Kaggle Notebook**.

---

## 📂 Estrutura do Repositório

```
├── modelo-de-redes-neurais-analise-rossmann.ipynb
├── README.md
```

---

## 🎯 Objetivo do Projeto

Demonstrar competência prática em **Machine Learning e Deep Learning**, aplicando modelos a um problema real de previsão de vendas, com foco em:

* Clareza de pipeline
* Comparação de abordagens
* Qualidade de código e organização

Este projeto foi desenvolvido como parte do meu **portfólio profissional**.

---

## ✍️ Autor

**Davi Freire**

Se você tiver sugestões ou quiser discutir melhorias no modelo, fique à vontade para abrir uma issue ou entrar em contato.

