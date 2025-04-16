# Intelig-ncia-Artificial
Matéria de inteligência artificial

# Aula 1
---

### **1. Introdução à Inteligência Artificial**

Inteligência Artificial (IA) é a área da ciência da computação que busca criar sistemas capazes de realizar tarefas que normalmente exigem inteligência humana, como reconhecer padrões, tomar decisões, entender linguagem natural e aprender com a experiência.

**Exemplos de aplicações:**

- Assistentes virtuais (Siri, Alexa)
    
- Sistemas de recomendação (Netflix, Spotify)
    
- Carros autônomos
    

---

### **2. História da IA**

- **1950** – Alan Turing propõe o "Teste de Turing", questionando se máquinas podem pensar.
    
- **1956** – O termo "Inteligência Artificial" é cunhado em uma conferência em Dartmouth.
    
- **Anos 60-70** – Primeiros programas de IA simbólica (como o ELIZA).
    
- **Anos 80** – Surgem os sistemas especialistas (baseados em regras).
    
- **Anos 90-2000** – Avanços em aprendizado de máquina e aumento de dados.
    
- **2010+** – Deep Learning ganha destaque com redes neurais profundas e grandes volumes de dados.
    

---

### **3. Diferença entre IA Simbólica, Machine Learning e Deep Learning**

|Tipo|Explicação simples|Exemplo|
|---|---|---|
|**IA Simbólica**|Usa regras explícitas, tipo "SE...ENTÃO..."|Sistema especialista médico|
|**Machine Learning (ML)**|A máquina aprende com dados em vez de seguir regras fixas|Previsão de preços de casas|
|**Deep Learning (DL)**|Um subconjunto de ML com redes neurais profundas, ideal para dados grandes e complexos|Reconhecimento facial, tradutores automáticos|

---

### **4. Algoritmos Clássicos de IA**

Alguns algoritmos não necessariamente envolvem aprendizado de máquina:

- **Busca em árvore**: como busca em largura (BFS) e profundidade (DFS)
    
- **Algoritmos de busca heurística**: A* (A estrela), usado em jogos e mapas
    
- **Sistemas especialistas**: com base de conhecimento e mecanismo de inferência
    
- **Algoritmos de lógica proposicional e lógica de predicados**
    

---

### **5. Conceitos de Inferência Estatística**

É a parte da estatística que tira conclusões sobre um conjunto de dados com base em uma amostra.

**Principais conceitos:**

- **Estimativa**: prever valores (média, variância)
    
- **Teste de hipóteses**: verificar se uma suposição estatística é válida
    
- **Intervalos de confiança**: margem de erro para estimativas
    
- **Correlação vs. causalidade**
    

Isso é fundamental para entender como os modelos de aprendizado são avaliados.

---

### **6. Aprendizado Supervisionado**

É um tipo de ML onde os dados têm **entradas (features)** e **saídas (rótulos)** já conhecidas.

**Exemplos:**

- Prever o preço de uma casa (com base em área, localização, etc.)
    
- Classificar e-mails como "spam" ou "não-spam"
    

**Algoritmos comuns:**

- Regressão linear/logística
    
- Árvore de decisão
    
- SVM
    
- Redes neurais
    

---

### **7. Aprendizado Não Supervisionado**

Aqui, os dados **não têm rótulos**. O objetivo é encontrar padrões ou estruturas escondidas.

**Exemplos:**

- Agrupar clientes com comportamentos parecidos (clustering)
    
- Reduzir a dimensionalidade de dados (como PCA)
    

**Algoritmos comuns:**

- K-means
    
- Hierarchical clustering
    
- DBSCAN
    
- PCA (Análise de Componentes Principais)---
# Aula 2
---
### **1. Introdução ao Aprendizado de Máquina**

Aprendizado de Máquina (ML) é um subcampo da IA onde algoritmos aprendem padrões a partir de dados para fazer previsões ou tomar decisões, sem serem explicitamente programados.

**Exemplo:** Um algoritmo que aprende a reconhecer dígitos escritos à mão a partir de imagens e seus respectivos rótulos (0 a 9).

---

### **2. Conceitos Fundamentais: Overfitting e Underfitting**

- **Overfitting (Sobreajuste)**: O modelo aprende _demais_, incluindo ruídos dos dados de treino, e vai mal nos dados novos.
    
- **Underfitting (Subajuste)**: O modelo é _simples demais_ e não consegue capturar os padrões dos dados nem mesmo no treino.
    

**Objetivo:** Encontrar um equilíbrio entre os dois.

---

### **3. Bias-Variance Tradeoff**

Esse é o dilema entre **viés (bias)** e **variância (variance)**:

- **Bias alto**: modelo muito simples → underfitting
    
- **Variância alta**: modelo muito complexo → overfitting
    

**O ideal é encontrar o ponto certo entre bias e variância** para ter um modelo que generaliza bem.

---

### **4. Redes Neurais Artificiais (ANN)**

São modelos inspirados no funcionamento do cérebro humano, compostos por **neurônios artificiais** conectados em **camadas**.

- Cada neurônio faz uma combinação dos dados de entrada e passa por uma função de ativação.
    
- ANN é a base de muitas técnicas modernas, como o **Deep Learning**.
    

---

### **5. Perceptron: O Primeiro Modelo de Rede Neural**

Criado por **Frank Rosenblatt**, é o modelo mais simples de uma rede neural:

- Tem uma camada de entrada e uma saída.
    
- É usado para **classificação binária**, como "sim/não", "spam/não spam".
    

Ele **só funciona para problemas linearmente separáveis**.

---

### **6. Multi-Layer Perceptron (MLP)**

É a evolução do Perceptron:

- Possui **múltiplas camadas ocultas** (por isso "multi-layer").
    
- Permite resolver **problemas não lineares**.
    
- Usa algoritmos como o **backpropagation** para treinar os pesos.
    

---

### **7. Deep Learning: Introdução**

Deep Learning é uma subárea de ML que utiliza **redes neurais profundas** (com muitas camadas) para lidar com problemas complexos, como:

- Reconhecimento de fala
    
- Visão computacional
    
- Tradução automática
    

É muito poderoso quando temos **grandes volumes de dados e poder computacional**.

---

### **8. Redes Convolucionais (CNN)**

Especializadas em **visão computacional** (imagens).

- Usam **filtros convolucionais** que detectam padrões visuais como bordas, formas, objetos.
    
- Aplicações: reconhecimento facial, detecção de objetos, diagnóstico por imagem médica.
    

---

### **9. Redes Recorrentes (RNN) e LSTMs**

Usadas para **dados sequenciais** (ex: texto, áudio, séries temporais).

- **RNN**: tem memória, mas sofre com problemas de longo prazo (desvanecimento do gradiente).
    
- **LSTM**: tipo de RNN que resolve isso, conseguindo **memorizar informações por mais tempo**.
    

**Exemplo:** previsão de palavras seguintes em uma frase.

---

### **10. Transformers: A Nova Fronteira**

Introduzidos em 2017 no artigo “Attention is All You Need”.

- São a base de modelos como o **GPT**, **BERT** e **ChatGPT**.
    
- Utilizam **mecanismos de atenção** para capturar dependências em qualquer posição da sequência de entrada (sem precisar de RNNs).
    
- São mais paralelizáveis e eficientes.
    

---

### **11. Transfer Learning: Aprendizado Transferido**

Consiste em **usar um modelo treinado em uma tarefa e adaptá-lo a outra**.

- Muito útil quando você tem **poucos dados**.
    
- Exemplo: pegar uma CNN treinada em milhões de imagens (como no ImageNet) e usá-la para classificar exames médicos.
    

---

### **12. AutoML: Automatizando o Aprendizado de Máquina**

AutoML visa **automatizar o processo de criar e ajustar modelos de ML**:

- Escolha de algoritmos
    
- Engenharia de atributos (feature engineering)
    
- Otimização de hiperparâmetros
    

Ferramentas populares: Google AutoML, Auto-sklearn, H2O.ai

---

### **13. Técnicas Avançadas de Aprendizado de Máquina**

Aqui entram técnicas modernas que potencializam o ML:

- **Ensemble Learning** (Random Forest, Gradient Boosting)
    
- **Reinforcement Learning** (aprendizado por tentativa e erro)
    
- **Anomaly Detection** (detecção de fraudes ou falhas)
    
- **Modelos generativos** (GANs, VAEs)
    
- **Explainable AI (XAI)**: tornar os modelos mais interpretáveis
    

---

---


Hierarchical clustering

DBSCAN

PCA (Análise de Componentes Principais)
