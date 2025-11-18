📊 Modelagem Estatística de Churn
--Fundamentos de Python aplicado a Data Science e IA
📘 1. Introdução

O objetivo é conduzir uma análise estatística completa da taxa de churn de uma empresa fictícia de telecomunicações utilizando:
Python, Pandas, Seaborn, Plotly, NumPy, Statsmodels (Regressão Logística)
O foco é entender quais fatores influenciam o cancelamento de clientes (churn) e gerar insights acionáveis para o negócio.
---
🏢 2. Problema de Negócio

A Connecta Telecom, empresa fictícia do setor de telecomunicações, enfrenta uma taxa de churn acima da média do mercado.
A diretoria precisa responder:
→ Quais são os principais fatores que levam os clientes a cancelar o serviço?
Isso envolve:
Modelagem Estatística → para entender relações entre variáveis
---
🎯 3. Objetivos do Projeto

✔ 1. Identificar fatores-chave
Entender quais variáveis têm impacto estatisticamente relevante no churn.
✔ 2. Quantificar o impacto
Mensurar quanto cada variável aumenta ou reduz o risco de churn.
✔ 3. Gerar recomendações práticas
Transformar os resultados estatísticos em estratégias de retenção de clientes.
📌 Modelo Utilizado:
Regressão Logística (Statsmodels)
— ideal para variáveis dependentes binárias como “Churn = Sim ou Não”.
---
🛠 4. Construção e Análise dos Dados

📌 4.1 Geração dos dados fictícios
Um dataset de 2000 clientes foi criado artificialmente com variáveis:
Fidelidade_Meses, Tipo_Contrato, Servico_Internet, Fatura_Mensal, Churn (0 = Não, 1 = Sim)
Os dados foram produzidos com lógica coerente de negócio para simular situações reais.

📌 4.2 Análise Exploratória (EDA)
Principais conclusões da EDA:
✔ Taxa de churn geral: ~49%, ✔ Clientes com faturas mais altas cancelam mais, ✔ Tipo de contrato tem forte impacto
Contrato mensal → muito mais churn, Contrato de dois anos → protege contra churn, ✔ Fidelidade baixa = alto risco de cancelamento e ✔ Fibra Óptica apresenta maior churn que DSL

Gráficos analisados no notebook:
Pizza plot (matplotlib e plotly), Histogramas, Boxplots por categoria, Barras agrupadas por contrato e churn, Distribuições por fidelidade e fatura

---
🔢 5. Preparação dos Dados para Modelagem Estatística

Para aplicar regressão logística, as variáveis categóricas foram transformadas em dummies:
Tipo_Contrato (Mensal, Anual, Dois anos), Servico_Internet (Fibra Óptica, DSL, Não)

E os dados foram divididos em:
X → variáveis independentes, y → variável dependente (churn)

Foi adicionada uma constante (intercepto) conforme exigido pela biblioteca statsmodels.

---
📈 6. Modelagem Estatística — Regressão Logística

A Regressão Logística foi escolhida para medir a força e direção do impacto de cada variável no churn.
Principais métricas extraídas:
Coeficientes (coef),Valores-p (P>|z|), Intervalos de confiança, Pseudo R² (≈ 0.645 — ótimo ajuste para este tipo de modelo)

---
📊 7. Interpretação dos Resultados (Business-Focused)

A partir dos coeficientes e das Razões de Chances (Odds Ratio):

🔍 Principais Findings
1. Tipo de Contrato (Mensal) — OR ≈ 195.18

Clientes com contrato mensal têm probabilidade 195 vezes maior de cancelar.
→ É o fator mais crítico do churn.

2. Tempo de Fidelidade — OR = 0.9459

Cada mês adicional reduz o churn em 5,4%.
→ Os primeiros meses são os mais importantes.

3. Fatura Mensal — OR = 1.0321

Cada unidade monetária aumenta o risco em ~3%.
→ Indício de sensibilidade a preço.

4. Serviço Fibra Óptica — OR = 4.2844

Usuários de fibra têm 4x mais chance de churn do que usuários DSL.
→ Pode sinalizar problemas técnicos ou expectativas não atendidas.

5. Serviço “Não” (sem internet) — OR ≈ 1.23

Aumenta um pouco o risco, mas com baixa significância estatística.

📌 Resumo Executivo (Para Recrutadores e Gestores)

O modelo mostrou com clareza que o churn é explicado principalmente por:

✔ Tipo de Contrato (mensal é extremamente arriscado)
✔ Tempo de Fidelidade
✔ Valor da Fatura
✔ Tipo de Serviço de Internet

🚀 8. Recomendações Estratégicas
Ação Recomendada	Justificativa	Impacto Esperado
Incentivar contratos de longo prazo	Contrato mensal aumenta churn em até 195x	Redução imediata do churn
Programa de fidelização nos primeiros meses	Cada mês reduz o churn em 5%	Aumenta retenção inicial
Revisão de preços para clientes com faturas elevadas	Fatura maior → +3% de churn por unidade	Reduz cancelamento por preço
Investigação sobre Fibra Óptica	4x mais churn	Melhorar qualidade e suporte

🏁 11. Conclusão

Este projeto demonstra:

domínio de Python aplicado à análise de dados

capacidade de conduzir projetos de EDA completos

entendimento de modelagem estatística real

capacidade de transformar resultados em insights de negócio

comunicação clara voltada para decisões estratégicas

Mostrando assim preparo para vagas em:

✔ Data Analyst
✔ Business Intelligence
✔ Data Scientist (nível inicial)
✔ Analytics / Insights

<h2>📲 Informações para contato!</h2>

[![Instagram](https://img.shields.io/badge/INSTAGRAM-pink?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/thiago.aires_/)
[![Gmail](https://img.shields.io/badge/GMAIL-333333?style=for-the-badge&logo=gmail&logoColor=white)](kbyteow@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thiago-assuncao-aires-moreira)


Meu Portfolio ! https://sites.google.com/view/portfolio-do-thiago?usp=sharing
