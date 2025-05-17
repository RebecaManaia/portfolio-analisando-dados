# CX Insights: Análise de Indicadores de Atendimento e Proposta de Melhoria Operacional

📊 Projeto de análise de indicadores de atendimento utilizando Python e Excel.

## 🎯 Objetivo
Explorar e entender como o TMA (Tempo Médio de Atendimento), o NPS (Net Promoter Score), o tempo de casa dos operadores e a supervisão impactam na percepção do cliente e nos resultados operacionais.

## 🛠️ Ferramentas utilizadas
- Python (Pandas, Matplotlib)
- Google Colab
- Excel
- GitHub

## 📈 Métricas analisadas
- NPS médio ponderado por quartil
- TMA por quartil e tempo de casa
- Comparativo entre novatos e veteranos
- Distribuição de quartis por supervisor
- % de operadores no Q4 (NPS mais crítico)
- NPS médio ponderado por supervisor
- Comparativo final entre TMA, % Q4, % novatos e NPS por equipe

## 🔍 Principais descobertas
- Maior TMA tende a estar presente nos quartis com pior NPS (Q4 e Q3)
- Novatos no Q1 de NPS apresentam TMA mais alto, indicando que emaptia e qualidade compensam a lentidão
- Times com maior % de novatos não necessariamente têm NPS mais baixo — reforçando a importância da liderança
- Vítor Hugo Cardoso e Manuela da Mota se destacam com melhores indicadores globais (verificar boas práticas)
- Os piores desempenhos por equipe estão com Leandro Moura, Rodrigo da Conceição e Igor Souza. Essas equipes enfrentam altos índices de clientes críticos (Q4), baixa nota média (NPS) e em dois casos, tempo médio de atendimento acima da média.


## 📂 Estrutura dos arquivos
- `BaseNPSeTMA.xlsx` → base de dados simulada
- `CX_Insights_Análise_de_Indicadores_de_Atendimento.ipynb` → notebook com cálculos, visualizações e interpretações
- `README.md` → descrição do projeto

---

📌 Projeto desenvolvido por [Rebeca Manaia](https://github.com/RebecaManaia)
