# 🚀 Introdução ao Databricks com Apache Spark, Delta Lake e MLflow

## 📚 Histórico

O **Databricks** foi fundado por criadores do **Apache Spark**, como uma plataforma unificada para engenharia, ciência de dados e machine learning na nuvem. Ele integra tecnologias como:

- **Apache Spark** – Processamento distribuído de dados em larga escala.
- **Delta Lake** – Armazenamento transacional para data lakes (ACID, versionamento, schema enforcement).
- **MLflow** – Gerenciamento de ciclos de vida de modelos de machine learning (experimentos, deployment, tracking).

---

## 📝 Criando uma Conta Gratuita no Databricks (Community Edition)

A Community Edition é ideal para fins de estudo e testes.

1. Acesse: [https://community.cloud.databricks.com](https://community.cloud.databricks.com)
2. Clique em **"Sign Up"** e preencha os dados.
3. Confirme o e-mail e acesse o ambiente gratuito com recursos limitados.

---

## 🏁 Iniciando um Projeto

1. Após o login, vá para o menu esquerdo e clique em:
   - **Workspace > Users > SeuNome**
   - Crie uma pasta: `meu_projeto`
   - Crie um **Notebook** dentro da pasta (ex: `analise_dados`)

2. Escolha o tipo de linguagem:
   - `Python`, `SQL`, `Scala` ou `R`

---

## ⚙️ Provisionando o Databricks: Criando um Cluster

1. Vá até a aba **Compute** e clique em **Create Cluster**
2. Dê um nome ao cluster (ex: `cluster-estudo`)
3. Mantenha o **Databricks Runtime** padrão (recomenda-se versão com ML)
4. Clique em **Create Cluster**

O cluster pode levar alguns minutos para iniciar.

---

## 🔍 Usando Spark para Analisar Dados

No notebook criado, conecte-se ao cluster e use Spark para ler e analisar dados. 

---

## ✅ Conclusão
Com o Databricks Community Edition, é possível experimentar na prática o ecossistema de Big Data e IA, usando Apache Spark para análise distribuída, Delta Lake para confiabilidade e MLflow para rastreamento de modelos.
