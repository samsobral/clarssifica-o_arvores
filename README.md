# Classificação de Dígitos MNIST com Árvores de Decisão e Florestas Aleatórias em R

Projeto desenvolvido como parte do laboratório da disciplina ME905, focado na construção de modelos preditivos para classificar os dígitos manuscritos (0, 1, 7 e 8) do dataset MNIST.

## 📌 Objetivo

Comparar o desempenho de modelos de árvore de decisão e florestas aleatórias implementadas manualmente em R para a tarefa de classificação de imagens de dígitos.

## 🛠️ Tecnologias Utilizadas

- Linguagem: **R**
- Bibliotecas: `rpart`, `caret`, `randomForest`, `ggplot2`, `dplyr`, `kableExtra`

## 📂 Estrutura do Projeto

- `data/`: Arquivos `.csv` com dados de treino e teste.
- `codigo/`: Script principal em RMarkdown com toda a análise.
- `relatorios/`: Relatório em PDF com as explicações e resultados.
- `output/`: Arquivo `.csv` com as previsões finais.
- `imagens/`: (opcional) Visualizações dos dígitos e erros de classificação.

## 📊 Principais Resultados

- **Árvore de Decisão:** acurácia de **91,3%**
- **Floresta Aleatória (100 árvores, mtry=28, profundidade=7):** acurácia de **95,1%**
- Foram analisados erros por classe e visões gráficas dos confundimentos entre classes similares como 0 e 8, 1 e 7.

## 💡 Destaques

- Modelagem manual da floresta aleatória sem uso direto do `randomForest`.
- Validação com `holdout` e `grid search` para ajuste fino de hiperparâmetros.
- Visualizações de imagens corretamente e incorretamente classificadas.

## 👤 Autor

Samuel Sobral Miller  
Estatístico | Cientista de Dados  


---

