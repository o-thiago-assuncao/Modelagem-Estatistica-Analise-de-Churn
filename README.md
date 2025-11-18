📊 Modelagem Estatística de Churn
--Fundamentos de Python aplicado a Data Science e IA
📘 1. Introdução

O objetivo deste projeto é conduzir uma análise estatística completa da taxa de churn de uma empresa fictícia de telecomunicações utilizando:

Python

Pandas

Seaborn

Plotly

NumPy

Statsmodels (Regressão Logística)

O foco é entender quais fatores influenciam o cancelamento de clientes (churn) e gerar insights acionáveis para o negócio.

🏢 2. Problema de Negócio

A Connecta Telecom, empresa fictícia do setor de telecomunicações, enfrenta uma taxa de churn acima da média do mercado.

A diretoria precisa responder:

Quais são os principais fatores que levam os clientes a cancelar o serviço?

Para isso utilizamos:

Modelagem Estatística → entender relação entre variáveis

(Opcional) Modelagem Preditiva → caso quiséssemos prever churn

🎯 3. Objetivos do Projeto
✔ 1. Identificar fatores-chave

Quais variáveis afetam significativamente o churn?

✔ 2. Quantificar o impacto

Quanto cada variável aumenta ou reduz o risco de churn?

✔ 3. Gerar recomendações práticas

Transformar resultados estatísticos em ações reais para retenção.

📌 Modelo Utilizado

Regressão Logística (Statsmodels) — ideal para variável dependente binária.

🛠 4. Construção e Análise dos Dados
📌 4.1 Geração dos Dados Fictícios

Um dataset de 2000 clientes foi criado artificialmente com variáveis como:

Fidelidade_Meses

Tipo_Contrato

Servico_Internet

Fatura_Mensal

Churn (0 = Não, 1 = Sim)

Os dados simulam cenários reais de comportamento de clientes.

📌 4.2 Análise Exploratória (EDA)

Principais conclusões:

✔ Taxa de churn geral: ~49%

✔ Clientes com faturas mais altas cancelam mais

✔ Contrato mensal → muito mais churn

✔ Contrato de dois anos → protege

✔ Fidelidade baixa = alto risco de cancelamento

✔ Fibra Óptica → maior churn que DSL

Gráficos gerados:

Pizza plot (matplotlib e plotly)

Histogramas

Boxplots

Barras agrupadas

Distribuições por fidelidade e fatura

🔢 5. Preparação dos Dados

Variáveis categóricas transformadas em dummies

Exclusão de colunas irrelevantes

Separação entre X (variáveis independentes) e y (churn)

Inclusão do intercepto para regressão logística

📈 6. Modelagem Estatística – Regressão Logística

Extração das principais métricas:

Coeficientes

Valores-p

Intervalos de confiança

Pseudo R² (≈ 0.645, excelente para churn)

📊 7. Interpretação dos Resultados
🔍 Principais Findings (Odds Ratio)
1. Tipo de Contrato Mensal — OR ≈ 195.18

→ Clientes com contrato mensal têm 195 vezes mais chance de cancelar.

2. Fidelidade — OR = 0.9459

→ Cada mês adicional reduz o churn em 5,4%.

3. Fatura Mensal — OR = 1.0321

→ Aumenta ~3% o risco de cancelamento por unidade monetária.

4. Fibra Óptica — OR = 4.2844

→ Clientes de fibra têm 4x maior chance de churn.

5. Serviço “Não” — OR ≈ 1.23

→ Leve aumento, porém não estatisticamente robusto.

📌 Resumo Executivo (Para Recrutadores e Gestores)

O churn é explicado principalmente por:

✔ Tipo de Contrato

✔ Tempo de Fidelidade

✔ Fatura Mensal

✔ Tipo de Serviço de Internet

🚀 8. Recomendações Estratégicas
Ação Recomendada	Justificativa	Impacto Esperado
Incentivar contratos de longo prazo	Churn 195x maior em contratos mensais	Redução imediata do churn
Programa para novos clientes	+ Fidelidade → - churn	Retenção nos primeiros meses
Revisão de preços	Faturas maiores → mais churn	Reduz cancelamento por preço
Investigar Fibra Óptica	4x mais churn	Melhorar suporte/técnico
🏁 9. Conclusão

Este projeto demonstra:

domínio de Python aplicado a dados,

capacidade de conduzir EDA completa,

habilidade em modelagem estatística real,

comunicação clara com foco em decisão de negócio,

preparação sólida para vagas como:
✔ Data Analyst
✔ BI Analyst
✔ Junior Data Scientist
✔ Analytics

<h2>📲 Informações para contato!</h2>

[![Instagram](https://img.shields.io/badge/INSTAGRAM-pink?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/thiago.aires_/)
[![Gmail](https://img.shields.io/badge/GMAIL-333333?style=for-the-badge&logo=gmail&logoColor=white)](kbyteow@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thiago-assuncao-aires-moreira)


Meu Portfolio ! https://sites.google.com/view/portfolio-do-thiago?usp=sharing
