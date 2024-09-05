# Twitter-sentiment-analysis

## 1. Introdução

### 1.1. Contexto
O Twitter é uma plataforma de mídia social amplamente utilizada, onde os usuários compartilham opiniões, notícias e pensamentos em tempo real. Analisar sentimentos expressos em tweets pode fornecer insights valiosos sobre a percepção pública sobre diversos temas.

### 1.2. Objetivo
O objetivo deste projeto é realizar uma análise de sentimentos dos tweets relacionados a um tópico específico, utilizando técnicas de processamento de linguagem natural (NLP) e modelagem preditiva. Buscamos construir um modelo que classifique os sentimentos dos tweets em categorias como positivo, negativo e neutro.

### 1.3. Justificativa
Compreender os sentimentos expressos nos tweets pode ajudar empresas, pesquisadores e interessados a monitorar a opinião pública e responder de forma mais eficaz a eventos e tendências. Este estudo também proporciona uma oportunidade para aprimorar habilidades em NLP e modelagem de dados.

## 2. Metodologia

### 2.1. Coleta e Preparação dos Dados
Os dados foram coletados kaggle.

**Passos:**
- **Importação dos Dados:** Carregamos o conjunto de tweets e realizamos uma análise inicial para familiarização.
- **Limpeza dos Dados:** Tratamos valores nulos, normalizamos o texto e removemos elementos irrelevantes, como URLs e menções.
- **Preprocessamento:** Aplicamos técnicas de lematização e remoção de stopwords para preparar os dados para a análise.

### 2.2. Análise Exploratória

**Gráficos e Insights:**
- **Distribuição dos Sentimentos:** Utilizamos gráficos de barras e nuvens de palavras para visualizar a frequência dos sentimentos e os termos mais comuns.
- **Análise de Termos:** Aplicamos a técnica de TF-IDF para ajustar a importância das palavras e identificar termos significativos.

### 2.3. Modelagem Preditiva

**Modelo de Regressão Logística:**
- **Preparação dos Dados:** Convertendo textos em vetores utilizando TF-IDF e N-grams.
- **Treinamento do Modelo:** Aplicamos a regressão logística para classificar os sentimentos dos tweets.
- **Avaliação:** Utilizamos métricas como acurácia.

## 3. Resultados e Discussão

### 3.1. Resultados do Modelo
Os resultados mostraram a eficácia do modelo em classificar os sentimentos dos tweets. Analisamos a importância das variáveis e a precisão do modelo.

### 3.2. Interpretação dos Resultados
- **Impacto das Características:** O modelo indicou quais características dos tweets (como presença de certas palavras) são mais influentes na determinação do sentimento.
- **Precisão do Modelo:** As métricas de avaliação forneceram uma visão detalhada da precisão do modelo e áreas para possíveis melhorias.

## 4. Conclusão

### 4.1. Principais Descobertas
O modelo foi capaz de capturar e classificar os sentimentos dos tweets com uma precisão significativa. A análise revelou insights sobre os sentimentos predominantes e as características dos textos.

### 4.2. Limitações e Trabalhos Futuros
**Limitações:**
- Dados limitados a tweets coletados em um período específico.
- Potenciais viéses devido a linguagem informal e abreviações nos tweets.

**Trabalhos Futuros:**
- Expandir a coleta de dados para incluir mais tópicos e períodos de tempo.
- Experimentar com técnicas de aprendizado profundo para melhorar a precisão da análise de sentimentos.

## Contato
Para mais informações, entre em contato através do paparellilucas1@gmail.com

