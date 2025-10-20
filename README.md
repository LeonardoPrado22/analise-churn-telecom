# Projeto 1 — Análise e Pré-Processamento de CHURN (Telecom)

Este projeto foi desenvolvido como parte do curso de Cientista de Dados da EBAC, consolidando as etapas iniciais de Pré-Processamento e Análise Exploratória (EDA).

---

## 🎯 Objetivos
O principal objetivo deste projeto é a **prática técnica** e a consolidação do conhecimento nas seguintes etapas fundamentais de análise:

* **Pré-processamento de Dados:** Aprender a identificar, analisar e realizar o tratamento de dados faltantes (missing values) no dataset.
* **Análise Exploratória de Dados (EDA) de Variáveis Preditivas:** Obter uma compreensão inicial da estrutura e da distribuição das variáveis, com **foco na relação dessas variáveis com o CHURN (Análise Bivariada Básica)**.

---

## 💻 Tecnologias Usadas
* **Linguagem:** Python
* **Bibliotecas Principais:** Pandas, NumPy, Matplotlib e Seaborn.
* **Ambiente:** Jupyter Notebook.

---

## 📈 Principais Análises Realizadas
O conteúdo dos notebooks (`PratiqueM14` e `PratiqueM15`) foca na execução prática dos seguintes passos:

* **Tratamento de Missing Values:** Identificação e estratégia de manejo de valores ausentes em colunas como `Genero`, `Pagamento_Mensal` e `PhoneService`.
* **Estatística Descritiva:** Uso da função `.describe()` para resumir as principais tendências e dispersão dos dados numéricos.
* **Análise de Distribuição e Bivariada Básica:** Realização de análises univariadas e **bivariadas** para mapear a distribuição das características e a **relação inicial de Churn** com as variáveis-chave (Contrato, Tenure, etc.).

---

## ✨ Insights Chave (Análise Primária)

Mesmo na fase inicial de EDA, foi possível extrair padrões críticos que direcionam uma futura modelagem preditiva e estratégias de retenção:

* **Contrato Mensal:** Clientes com **contratos mensais** (Month-to-month) apresentaram a taxa de cancelamento (**Churn**) significativamente mais alta em comparação com os contratos anuais e bienais, indicando a importância da fidelização inicial.
* **Tempo de Cliente (Tenure):** O tempo de permanência é inversamente proporcional ao risco de Churn, com o período **inicial (early tenure)** se mostrando um ponto crítico para o abandono do serviço.
* **Clientes Idosos (Senior):** Clientes seniors (idosos) apresentaram uma **proporção de Churn maior** que a média, sugerindo que este grupo demográfico merece atenção especial em futuras análises bivariadas.
