# 📊 Análise de Gastos Pessoais com Pandas

## 🧠 Contexto

Este projeto tem como objetivo aplicar, na prática, os principais conceitos de **Análise e Manipulação de Dados com Pandas**, utilizando um **dataset real de finanças pessoais**.

O cenário simula um trabalho comum de um **Analista de Dados Júnior**, no qual é necessário limpar dados financeiros, estruturar informações temporais e gerar insights que ajudem na tomada de decisão sobre hábitos de consumo.

O projeto foi desenvolvido como parte dos meus estudos em **Análise de Dados com Python**, com foco em **limpeza de dados, seleção, agrupamento e análise exploratória**.

---

## 📁 Dataset utilizado

* **Nome:** Personal Budget Transactions Dataset
* **Fonte:** Kaggle
* **Arquivo utilizado no notebook:** `budget_data.csv`

### Principais colunas do dataset (conforme usado no notebook):

* `date` — data da transação
* `category` — categoria do gasto
* `amount` — valor da transação (**já em formato numérico – float**)

ℹ️ Diferente de muitos datasets financeiros, **a coluna `amount` já vem tratada**, permitindo cálculos diretos desde o início da análise.

---

## 🎯 Objetivos do projeto

* Explorar um dataset real de gastos pessoais
* Verificar tipos de dados e valores ausentes
* Realizar análises agregadas de gastos
* Analisar padrões temporais de consumo
* Aplicar filtros para identificar gastos relevantes
* Gerar insights sobre hábitos financeiros

---

## 🛠️ Tecnologias utilizadas

* Python 3
* Pandas
* Jupyter Notebook

---

## 🧩 Etapas da análise

### 1️⃣ Importação e exploração inicial

* Importação da biblioteca Pandas
* Leitura do arquivo CSV
* Visualização das primeiras linhas (`head`)
* Verificação do tamanho do dataset (`shape`)
* Inspeção dos tipos das colunas (`info`)
* Checagem de valores nulos

### 2️⃣ Análise geral de gastos

* Cálculo do total gasto
* Cálculo do gasto médio

### 3️⃣ Análise por categoria

* Total gasto por categoria
* Identificação da categoria com maior volume de gastos

### 4️⃣ Análise temporal

* Agrupamento dos gastos por mês
* Análise da evolução dos gastos mensais
* Visualização em gráfico de linha

### 5️⃣ Filtros e seleções

* Identificação de gastos acima da média
* Análise específica da categoria **Restaurant**
* Ordenação dos maiores gastos

---

## 📊 Principais insights

* A maior parte dos gastos está concentrada em poucas categorias
* É possível identificar meses com picos claros de despesas
* Gastos acima da média ajudam a localizar despesas que mais impactam o orçamento
* A análise por categoria permite focar em áreas com maior potencial de economia

---

## ⭐ Análises adicionais

* Identificação dos **5 maiores gastos individuais**
* Ranking de categorias por volume total gasto
* Análise visual da evolução mensal dos gastos

---

## 📂 Estrutura do repositório

```
├── analise_de_gastos_pessoais.ipynb
└── README.md
```

---

## 🚀 Próximos passos

* Criar visualizações gráficas para os principais indicadores
* Comparar gastos entre anos diferentes
* Expandir o projeto com dados de renda

---

## 👤 Autor

**Filipe Madeira**
Estudante de Análise de Dados

🔗 GitHub: [https://github.com/FilipeMadeira13](https://github.com/FilipeMadeira13)
🔗 LinkedIn: [https://www.linkedin.com/in/carlos-filipe-madeira-de-souza-16211922a/](https://www.linkedin.com/in/carlos-filipe-madeira-de-souza-16211922a/)

---

📌 *Projeto desenvolvido para fins educacionais, com foco em aprendizado prático e construção de portfólio.*
