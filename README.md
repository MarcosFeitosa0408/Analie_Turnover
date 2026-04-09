# Analie_Turnover
Análise de Turnover usando IV (Information Value): identificando os principais fatores que influenciam a rotatividade de funcionários.
🔍 Análise de Fatores de Turnover com Information Value (IV)
Este projeto tem como objetivo identificar os principais fatores que influenciam o turnover (rotatividade de funcionários) em uma empresa, utilizando o cálculo de Information Value (IV) para medir a relevância das variáveis.

🧠 Objetivo
Aplicar técnicas de análise estatística e exploração de dados para descobrir quais variáveis possuem maior poder de discriminação do turnover, auxiliando estratégias de retenção de talentos dentro da empresa.

📊 Ferramentas Utilizadas
Excel (para análise exploratória e cálculo do IV)
Python (Pandas, Numpy – futuro notebook em construção)
Visualizações com tabelas e gráficos
GitHub como repositório e versionamento
🗂 Estrutura do Projeto
📁 turnover-analysis/
├── Turnover.xlsx           → Base de dados com variáveis e cálculos de IV
├── Turnover.png            → Tabela visual dos IVs e grau de influência
├── README.md               → Documentação do projeto
📌 Metodologia: Information Value (IV)
O IV mede o poder de uma variável em separar as classes de um problema binário (neste caso, colaboradores que saíram ou não). Quanto maior o IV, mais relevante a variável:

Intervalo de IV	Grau de Influência
IV > 0.30	Forte
0.10 < IV ≤ 0.30	Médio
0.02 < IV ≤ 0.10	Fraco
IV ≤ 0.02	Muito Fraco
✅ Principais Descobertas
As variáveis com IV Forte (alta influência no turnover):

Faz_hora_extras? → 0.40
Salário → 0.36
Tempo_de_carreira → 0.34
Idade → 0.31
Tempo_de_empresa → 0.30
Essas variáveis estão mais relacionadas à saída do colaborador e devem ser monitoradas com mais atenção em ações de RH.

As variáveis com IV Muito Fraco (pouco relevantes para prever turnover):

Anos_desde_a_ultima_promocao
Formação
Gênero
📎 Arquivos Importantes
Turnover.xlsx: Contém os dados e cálculos de IV.
Turnover.png: Imagem com a tabela final dos IVs e grau de influência.
🚀 Próximos Passos
Criar um notebook Python para automação do cálculo de IV.
Adicionar gráficos interativos com Power BI ou Plotly.
Explorar modelos de machine learning para previsão de turnover.
🙋‍♂️ AutorTurnover.xlsx
Marcos Antônio Feitosa
Estudante de Análise de Dados | Foco em Carreira Tech
LinkedIn (adicione seu link aqui)
GitHub: MarcosFeitosa0408 ![Turnover Visualization]![Turnover

📌 Este projeto é parte do meu portfólio de transição de carreira para a área de tecnologia com foco em dados e soluções inteligentes para negócios.
