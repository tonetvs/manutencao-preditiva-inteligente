# Manutenção Preditiva Inteligente em Máquinas Industriais

Este projeto apresenta uma solução avançada de manutenção preditiva utilizando aprendizado de máquina para prever a vida útil restante (RUL) e identificar antecipadamente falhas críticas em máquinas industriais. O sistema permite melhorar a confiabilidade, reduzir custos de parada e otimizar o planejamento de manutenção.

## Objetivo

- Estimar com precisão a vida útil restante das máquinas (RUL)
- Detectar falhas iminentes com alertas binários
- Apoiar decisões estratégicas de manutenção com base em dados

## Metodologia

1. **Pré-processamento:**
   - Limpeza de dados e remoção de colunas com alta taxa de nulos
   - Escalonamento com `StandardScaler`
   - Codificação de variáveis categóricas com `OneHotEncoder`

2. **Modelagem:**
   - Modelos testados: Random Forest, XGBoost, Rede Neural e Stacking
   - Previsão da variável contínua: `Remaining_Useful_Life_days`
   - Classificação da variável binária: `Falha_dentro_de_7_dias`

3. **Avaliação:**
   - Métricas para regressão: MAE, RMSE, R², Explained Variance
   - Métricas para classificação: Accuracy, Recall, F1-Score, AUC
   - Análises gráficas para validação e comparação dos modelos

## Bibliotecas Utilizadas

pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  
xgboost  
imblearn  
tensorflow / keras  
plotly

## Execução

O notebook já contém todos os resultados processados e pode ser executado via Google Colab ou Jupyter Notebook.

## Estrutura

manutencao-preditiva-maquinas/  
├── notebooks/  
│   └── Man_Predit_Maquinas.ipynb  
├── README.md  
├── requirements.txt  
└── LICENSE

## Autor

Heitor Tonet  
Engenheiro de Controle e Automação e Cientista de Dados, com foco em soluções inteligentes para manutenção preditiva, otimização de processos industriais e sistemas autônomos.

## Licença

Projeto disponibilizado sob a licença MIT.
