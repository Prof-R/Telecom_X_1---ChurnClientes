# 📊 Análise de Churn de Clientes na Telecom X

Este repositório contém os estudos, anotações e práticas realizadas durante a formação em **Data Science** promovida pelo programa **ONE - Oracle Next Education**, em parceria com a **Alura**.

> 🙏 Sou grato pela oportunidade de aprendizado proporcionada por essa formação!

---


Olá a todos!  
Sou o novo assistente de análise de dados na **Telecom X** e estou muito empolgado em fazer parte do projeto **Churn de Clientes**.

A Telecom X tem enfrentado um desafio significativo: **altos índices de cancelamentos de clientes**. Este projeto tem como objetivo compreender os fatores que levam à evasão e, com isso, desenvolver **estratégias eficazes de retenção**.

---

## 🚀 Objetivos do Projeto

Este projeto tem como foco a **Análise Exploratória de Dados (EDA)** para:

- Coletar e tratar dados relevantes.
- Garantir a qualidade e consistência das informações.
- Explorar padrões e comportamentos associados ao churn.
- Gerar **insights acionáveis** que servirão como base para modelos preditivos futuros.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python**
- **Pandas** – Manipulação de dados
- **Matplotlib / Seaborn** – Visualização de dados
- **Requests / JSON** – Consumo de dados via API

---

## 📅 Cronograma de Trabalho

1. **Importar e manipular dados** via API.
2. **Aplicar conceitos de ETL**: Extração, Transformação e Carga.
3. **Criar visualizações estratégicas** com gráficos e tabelas.
4. **Realizar EDA** e documentar os principais insights.

---

## 📌 Etapas do Projeto

### 1. Extração de Dados

- Importação dos dados da API da **Telecom X**, em formato JSON.
- Conversão dos dados para um **DataFrame Pandas**.

### 2. Transformação

#### 🔍 Verificação de Inconsistências

- Identificação de valores nulos, duplicados, erros de formatação e categorias incorretas.

#### 🔢 Estudo das Variáveis

- Exploração da estrutura do dataset.
- Identificação das colunas mais relevantes para a evasão.

#### 🛠️ Tratamento de Dados

- Correção de inconsistências.
- **Criação da coluna "Contas Diárias"** a partir do faturamento mensal.
- Padronização de categorias: ex. transformar "Sim"/"Não" em 1/0.
- Tradução e renomeação de colunas para melhor clareza.

---

## 📊 Carga e Análise de Dados

### 📈 Análise Descritiva

- Cálculo de métricas: média, mediana, desvio padrão, mínimo, máximo e quartis.
- Compreensão geral do comportamento dos clientes.

### 💡 Distribuição da Evasão

- Análise gráfica da proporção entre clientes que ficaram e os que cancelaram.

### 🧑‍💼 Evasão por Variáveis Categóricas

- Gênero, tipo de contrato, forma de pagamento, etc.
- Identificação de perfis com maior tendência de churn.

### 💰 Evasão por Variáveis Numéricas

- Análise de "tempo de contrato", "total gasto", etc.
- Verificação de valores que mais se associam ao churn.

### 🔗 Correlação entre Variáveis

Utilização da função `corr()` do **Pandas**:

- Geração da **matriz de correlação**.
- Identificação de fatores com maior relação com o churn.

#### Interpretação da Correlação de Pearson:

- `+1`: Correlação positiva perfeita
- `-1`: Correlação negativa perfeita
- `0`: Ausência de correlação linear

---

## 📌 Conclusão

Com base nesta análise exploratória, esperamos:

- Obter uma compreensão profunda do comportamento dos clientes.
- Apoiar a equipe de Data Science na construção de modelos preditivos.
- Contribuir de forma significativa para a **retenção de clientes** na Telecom X.

---

## 🧠 Futuras Etapas

- Implementação de modelos de Machine Learning para previsão de churn.
- Geração de dashboards interativos para visualização de métricas em tempo real.
- Aplicação de estratégias automatizadas de retenção baseadas nos perfis de risco.

---

## 🤝 Contribuição

Este repositório faz parte de um estudo de caso interno e pode ser usado como referência para projetos de EDA e análise de churn.

Sinta-se à vontade para abrir issues ou contribuir com melhorias!

---

Referências:

[Visite o site da ONE - Oracle Next Education](https://www.oracle.com/br/education/oracle-next-education/)

[Visite o site da Alura](https://www.alura.com.br)

---

## 📬 Contato

Caso tenha dúvidas ou sugestões, entre em contato:  
📧 **robney@gmail.com**

---

> _“Dados bem analisados têm o poder de transformar decisões.”_
