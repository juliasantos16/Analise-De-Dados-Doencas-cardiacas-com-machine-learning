# Descrição:

Este projeto usa machine learning para analisar dados clínicos e prever o risco de doenças cardíacas. A ideia é transformar números e estatísticas em insights valiosos que possam ajudar na prevenção e no diagnóstico precoce.

# 💡 Como isso funciona?
# 📊 Analisamos os dados
Pegamos informações como idade, pressão arterial, colesterol, glicose, tabagismo e hábitos de vida para entender padrões e relações entre eles.

# 🛠️ Preparamos tudo para o modelo
Limpamos e organizamos os dados, garantindo que estejam prontos para serem processados por um modelo de Machine Learning.

# 🤖 Treinamos um modelo inteligente
Utilizamos o algoritimo chamado Random Forest, que aprende com os dados e consegue identificar quais fatores são mais relevantes na previsão de doenças cardíacas.

# 🔍 Interpretamos os resultados
Usamos técnicas como o SHAP para mostrar quais fatores tiveram mais peso na decisão do modelo.




# 📊 Estrutura do Projeto

## Análise Geral dos Dados
- O conjunto de dados contém variáveis como idade, altura, peso, pressão arterial, colesterol, glicose, tabagismo, consumo de álcool e atividade física.
- Análise estatística e visualização dos dados para entender distribuições e correlações.

## Pré-processamento
- Tratamento de valores ausentes e inconsistentes.
- Normalização e codificação de variáveis categóricas.
- Balanceamento dos dados para evitar viés no modelo.

## Treinamento de Modelos
- Teste com diferentes algoritmos de Machine Learning, como Regressão Logística, Random Forest, e Redes Neurais.
- Ajuste de hiperparâmetros para otimizar a performance.

## Avaliação e Resultados
Comparação de métricas como acurácia, precisão, recall e F1-score.
Análise da importância das features na predição da doença.

## 🚀 Tecnologias Utilizadas
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn

  ## Todas as Bibliotecas utilizadas:

- pandas, numpy, matplotlib, plotly (para manipulação e visualização de dados)
- shap (para interpretabilidade do modelo)
- scikit-learn (train_test_split, classification_report, permutation_importance)
- RandomForestClassifier (modelo de machine learning utilizado)
