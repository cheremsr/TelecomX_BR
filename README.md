# 📊 Telecom X - Análise de Evasão de Clientes 

Este projeto faz parte do desafio **Telecom X** da Alura, cujo objetivo é aplicar técnicas de **ETL** (Extração, Transformação e Carga) e **EDA** (Análise Exploratória de Dados) para entender os fatores que influenciam a evasão de clientes (churn) em uma empresa de telecomunicações.

---

## 🚀 Objetivos

- Extrair dados de uma base fornecida em JSON.
- Realizar o tratamento e transformação dos dados.
- Aplicar análise exploratória de dados (EDA) com visualizações.
- Identificar padrões e comportamentos associados ao churn.
- Apresentar sugestões com base nos achados.

---

## 🧰 Tecnologias Utilizadas

- Pandas
- Google Colab / Jupyter Notebook

---

## 🗂️ Organização dos Dados

Os dados dos clientes estão estruturados em JSON e incluem:

- **Informações Pessoais**: gênero, idade, parceiro, dependentes.
- **Serviços Contratados**: telefonia, internet, segurança online, suporte técnico.
- **Informações de Conta**: tipo de contrato, forma de pagamento, cobrança mensal e total.
- **Churn**: se o cliente deixou ou não a empresa.

Para mais detalhes, consulte o arquivo `Telecomx-Lorelaine`.

---

## 📈 Análises Realizadas

- Distribuição geral de clientes que cancelaram (`Churn`).
- Churn por tipo de contrato (mensal, anual, bianual).
- Análise de gastos mensais entre clientes ativos e cancelados.
- Exploração dos principais serviços associados ao churn.

---

## 🧠 Principais Insights

- Contratos **mensais** têm maior taxa de evasão.
- Clientes com **gastos mensais elevados** estão mais propensos ao churn.
- **Internet via fibra óptica** aparece com frequência entre os clientes que cancelam.

---

## 💡 Sugestões

- Criar incentivos para migração para contratos de longo prazo.
- Oferecer benefícios para clientes com altos gastos mensais.
- Monitorar de forma proativa os perfis com maior risco de evasão.


