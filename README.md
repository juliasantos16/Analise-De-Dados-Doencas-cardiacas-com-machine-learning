# Data-Analysis-Heart-Diseases-with-machine-learning

## 📊 Exploratória dos Dados
Carreguei o arquivo cardio_train.csv e dele se obteve um entendimento das características das variáveis. As principais étapas incluem:

**Visualização inicial:** Com uso do head() para visualizar as primeiras linhas do dataset.

**Informações gerais:** Com info() e describe() para obter as estatísticas descritivas das variáveis.

**Mudança de unidade para a idade:** A idade estava apresentada em dias, eu a converti para anos, facilitando sua interpretação e obtenção de média de idade.

**Verificação de valores NaN:** Nenhum NaN foi encontrado, ou seja, que o dataset está completo e não faltou informação.

## 🔍 Análise Exploratória dos Dados (EDA)
A Análise Exploratória de Dados (EDA) foi utilizada para encontrar padrões, anomalias e ter um insight preliminar sobre o dataset.

**Dados numéricos**
Uso de gráficos de boxplot para visualização da distribuição de variáveis como a idade (em anos), do peso, da pressão arterial sistólica e diastólica. Ferramentas: Plotly para a criação de gráficos interativos.

**Dados categóricos**
Visualização da distribuição das categorias para variáveis como gênero, colesterol, glicose, tabagismo, consumo de álcool e nível de atividade física. Foram usados gráficos de barras para facilitar a interpretação 

## 🤖 Construção do Modelo de Machine Learning
**Preparação dos Dados**
Definição das variáveis:
Y: variável alvo representando a presença (1), ou ausência (0), das doenças cardíacas.
X: conjunto de características preditivas.
Divisão dos dados: separação nos conjuntos de treino e teste usando a função train_test_split (33% para teste).

**Treinamento do Modelo**
Algoritmo utilizado: RandomForestClassifier do scikit-learn, com 20 estimadores e profundidade máxima de 4. O modelo foi treinado para identificação de padrões e para prever o risco de doenças do coração a partir das variáveis do dataset. 
