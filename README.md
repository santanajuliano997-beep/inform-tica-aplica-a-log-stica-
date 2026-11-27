# 📊 Informática Aplicada à Logística

Portfólio de projetos de análise de dados desenvolvidos na disciplina de **Informática Aplicada à Logística** (Fatec – Logística), organizado por trimestre.

`Excel` | `Power BI` | `Python` | `Google Colab` | `Regressão Linear` | `Dados Abertos`

---

## 🗂️ Sumário

| Etapa | Nº | Projeto | Ferramenta |
|---|---|---|---|
| **MVP 1 — 1º Trimestre** | 1 | [Tratamento de dados ANTT – Transporte Multimodal](#1-tratamento-de-dados-abertos-antt--transporte-multimodal) | Excel |
| | 2 | [Dashboard de Transportes Multimodais](#2-dashboard-de-transportes-multimodais-no-power-bi) | Power BI |
| | 3 | [Censo 2022 – Favelas e Comunidades de SP](#3-análise-do-censo-2022-favelas-e-comunidades--sp) | Excel |
| | 4 | [Dashboard de Habilitações (CNH – SP)](#4-dashboard-de-análise-de-habilitações-cnh--sp) | Power BI |
| **MVP 2 — 2º Trimestre** | 5 | [Dashboard de CNH com figuras por gênero](#5-dashboard-com-figuras-análise-de-habilitações-cnh--sp) | Power BI |
| | 6 | [Regressão linear: Excel × Google Colab (Sorvetes)](#6-regressão-linear-comparando-excel-e-google-colab) | Excel + Python |
| | 7 | [Curso ENAP – Power BI para Gestão](#7-curso-aplicação-do-power-bi-para-aprimoramento-da-gestão--enap) | Certificado |
| | 8 | [Regressão linear: horas de estudo × nota](#8-regressão-linear-no-excel-horas-de-estudo--nota) | Excel |
| | 9 | [Prova: regressão idade ao casar (homens × mulheres)](#9-prova--regressão-linear-simples-idade-média-ao-casar) | Excel |
| | 10 | [Prova: dashboard de investimentos](#10-prova--dashboard-de-investimentos) | Power BI |

---

### 🛠️ Ferramentas Utilizadas
- **Excel:** tratamento de dados, fórmulas, tabelas dinâmicas, gráficos e regressão linear.
- **Power BI:** modelagem de dados, mapas e relatórios interativos.
- **Python (Google Colab):** `pandas`, `scikit-learn` e `matplotlib` para regressão linear.

---

# 🟦 MVP 1 — 1º Trimestre

> Foco: **coleta, tratamento e visualização de dados abertos** com Excel e Power BI.

#### 1. Tratamento de Dados Abertos (ANTT – Transporte Multimodal)
- **Objetivo:** coletar e tratar os dados públicos da ANTT sobre os Operadores de Transporte Multimodal (OTM) registrados no país.
- **Base:** 1.382 empresas cadastradas, com razão social, CNPJ, endereço, UF, COTM e validade do registro.
- **Entregáveis:** planilha estruturada e tabela dinâmica com a contagem de empresas por UF.
- **Principais resultados:** **SP lidera com 569 empresas**, seguido de RJ (110), AM (98), RS (82) e PR (74). Quase todas as empresas (1.375) têm origem no Brasil.
- **Arquivo:** [`operador_transporte_multimodal.xlsx`](operador_transporte_multimodal.xlsx)

<img width="567" height="428" alt="Planilha ANTT multimodal" src="https://github.com/user-attachments/assets/1ae7015d-71c1-4502-af77-88cf8896b0d6" />

#### 2. Dashboard de Transportes Multimodais no Power BI
- **Objetivo:** transformar a base tratada na Atividade 1 em um relatório visual e interativo.
- **Entregáveis:** dashboard no Power BI com a distribuição das empresas por estado e filtros para explorar o setor.
- **Arquivo:** [`empresasmultimodais 1.pbix`](empresasmultimodais%201.pbix)

<img width="1316" height="738" alt="Dashboard multimodal" src="https://github.com/user-attachments/assets/63d869b5-0be8-4659-b765-69dd302d8c23" />

#### 3. Análise do Censo 2022 (Favelas e Comunidades – SP)
- **Objetivo:** explorar os dados do Censo 2022 (IBGE) sobre favelas e comunidades urbanas no estado de São Paulo.
- **Base:** 92 municípios paulistas, com 3.123 favelas/comunidades no total.
- **Entregáveis:** planilha com rankings de população e densidade, análise de correlação e respostas às perguntas da atividade.
- **Principais resultados:**
  - Maior população: **São Paulo** (1.728.265 habitantes em favelas/comunidades).
  - Maior densidade: **Diadema** (403,9 hab/ha).
  - População total analisada: **3.630.519** pessoas.
  - A população parda representa **52,2%** do total.
  - Correlação entre número de favelas/comunidades e população: **r = 0,998** (muito forte).
- **Arquivo:** [`Atividade_Logistica_Favelas_Comunidades_v2.xlsx`](Atividade_Logistica_Favelas_Comunidades_v2.xlsx)

<img width="610" height="673" alt="Censo 2022 favelas SP" src="https://github.com/user-attachments/assets/98da4c3b-4c48-463a-a305-290c90cb7329" />

#### 4. Dashboard de Análise de Habilitações (CNH – SP)
- **Objetivo:** fazer um estudo descritivo da distribuição e do perfil dos condutores habilitados no estado de São Paulo.
- **Entregáveis:** dashboard no Power BI com métricas e insights sobre a base de condutores paulistas.
- **Arquivo:** [`analise CNH SP.pbix`](analise%20CNH%20SP.pbix)

<img width="1430" height="802" alt="Dashboard CNH SP" src="https://github.com/user-attachments/assets/92300bb5-0d10-412a-8356-eae0229d2879" />

---

# 🟩 MVP 2 — 2º Trimestre

> Foco: **visualização avançada no Power BI** e **modelos de regressão linear** no Excel e em Python.

#### 5. Dashboard com Figuras: Análise de Habilitações (CNH – SP)
- **Objetivo:** evoluir o dashboard da Atividade 4 com ícones personalizados para representar o gênero dos condutores.
- **Entregáveis:** relatório no Power BI com figuras masculina e feminina, facilitando a leitura da proporção de condutores por gênero em SP.
- **Arquivos:** [`analise CNH SP.pbix`](analise%20CNH%20SP.pbix), [`male.png`](male.png), [`female.png`](female.png)

<img width="1430" height="798" alt="Dashboard CNH figuras 1" src="https://github.com/user-attachments/assets/042d4de7-1b53-4600-9bbf-049eda5bed3e" />
<img width="1426" height="795" alt="Dashboard CNH figuras 2" src="https://github.com/user-attachments/assets/d65fac98-b18e-4107-a464-74b8636f99b6" />

#### 6. Regressão Linear: comparando Excel e Google Colab
- **Objetivo:** prever o faturamento de uma sorveteria (`Revenue`) a partir da temperatura (`Temperature`) e comparar o resultado do Excel com um modelo em Python no Google Colab.
- **Base:** 500 observações de temperatura (°C) e faturamento ($).
- **Entregáveis:** notebook no Colab com análise exploratória, divisão treino/teste (80/20), treino do modelo, métricas, reta de regressão, análise de resíduos e previsões.
- **Principais resultados:**

| | Excel (todos os dados) | Colab (treino 80% / teste 20%) |
|---|---|---|
| Equação | Revenue = 50,23 + 20,89 × Temp. | Revenue = 54,00 + 20,73 × Temp. |
| R² | 0,865 | 0,897 (no teste) |
| Correlação (r) | 0,93 | 0,93 |
| MAE / RMSE | — | 24,90 / 56,28 |

- **Conclusão:** as duas ferramentas chegam a modelos praticamente iguais. Cada **1 °C a mais aumenta o faturamento em cerca de $21**, e a temperatura explica cerca de 86% a 90% da variação das vendas. Previsões: 25 °C ≈ $572, 30 °C ≈ $676 e 35 °C ≈ $780.
- **Arquivos:** [`Ice Cream 1.xlsx`](Ice%20Cream%201.xlsx), [`Regressao_Linear_Ice_Cream.ipynb`](Regressao_Linear_Ice_Cream.ipynb)
- **Notebook no Colab:** [abrir no Google Colab](https://colab.research.google.com/drive/1KsvG_PbBHfClFMpE8TfbnrKWprkNQKvo)

<img width="1919" height="1029" alt="Regressão sorvete 1" src="https://github.com/user-attachments/assets/2f47ed7b-b3e9-42d9-9c42-6c4252c064ef" />
<img width="1916" height="942" alt="Regressão sorvete 2" src="https://github.com/user-attachments/assets/f191db7a-196f-48be-ab93-ae8d73fa6c6d" />
<img width="1919" height="944" alt="Regressão sorvete 3" src="https://github.com/user-attachments/assets/919f13c7-9f18-4102-8cdf-7c2cb967d58e" />
<img width="1919" height="946" alt="Regressão sorvete 4" src="https://github.com/user-attachments/assets/df63cef1-1ed4-44ce-9241-c90827c72119" />
<img width="1919" height="945" alt="Regressão sorvete 5" src="https://github.com/user-attachments/assets/d1416089-db56-4423-955b-e917108ff950" />

#### 7. Curso Aplicação do Power BI para Aprimoramento da Gestão – ENAP
- **Objetivo:** aprofundar os conhecimentos em Power BI aplicados à gestão e à tomada de decisão.
- **Instituição:** ENAP (Escola Nacional de Administração Pública)
- **Carga horária:** 25 horas (turma out/2026)
- **Entregável:** certificado de conclusão.

<img width="1116" height="791" alt="Certificado ENAP 1" src="https://github.com/user-attachments/assets/5c2936ea-6d04-41ca-91e8-1dd02736b2d1" />
<img width="1118" height="790" alt="Certificado ENAP 2" src="https://github.com/user-attachments/assets/d74d068b-8bdd-43da-8ec2-1263b3a5ba90" />

#### 8. Regressão Linear no Excel: Horas de Estudo × Nota
- **Objetivo:** treino para a prova. Verificar se mais horas de estudo levam a notas maiores usando regressão linear simples no Excel.
- **Base:** 200 alunos, com horas de estudo, horas de sono, frequência, notas anteriores e nota da prova.
- **Entregáveis:** planilha com coeficientes, qualidade do ajuste, teste de significância, notas previstas e resíduos.
- **Principais resultados:**
  - Equação: **Nota = 23,62 + 1,634 × Horas de estudo**
  - Cada hora a mais de estudo soma cerca de **1,63 ponto** na nota.
  - r = 0,777 e **R² = 0,603**: as horas de estudo explicam cerca de 60% da variação das notas.
  - t = 17,35 e valor-p ≈ 0: a relação é **positiva e estatisticamente significativa**.
  - Exemplo: com 10 h de estudo, a nota prevista é **≈ 39,96**.
- **Arquivo:** [`regressao_horas_estudo_x_nota.xlsx`](regressao_horas_estudo_x_nota.xlsx)

<img width="1919" height="1030" alt="Regressão horas x nota" src="https://github.com/user-attachments/assets/91ef388e-a5e9-4070-bc65-edfb1ff4ba1f" />

#### 9. Prova – Regressão Linear Simples: Idade Média ao Casar
- **Enunciado:** modelo de regressão linear simples com a idade média dos homens ao casar (x) e a idade média das mulheres ao casar (y).
- **Objetivo:** medir a relação entre a idade dos homens e a das mulheres ao casar e estimar a idade média das mulheres a partir da idade média dos homens.
- **Entregáveis:** gráfico de dispersão com linha de tendência, equação da reta, coeficiente de determinação (R²) e interpretação dos resultados.

<img width="1919" height="1015" alt="Prova regressão idade ao casar" src="https://github.com/user-attachments/assets/6f52b96a-6a29-46b9-bc4c-5a3432374b3b" />

#### 10. Prova – Dashboard de Investimentos
- **Enunciado:** construir um relatório (dashboard) com, no mínimo, três visualizações diferentes:
  - mapa geográfico mostrando onde há o maior número de investimentos;
  - visualização relacionando município e setor econômico envolvido;
  - visualização de livre escolha.
- **Objetivo:** identificar onde os investimentos estão concentrados e quais setores econômicos se destacam em cada município.
- **Entregáveis:** dashboard no Power BI com mapa geográfico, gráfico município × setor econômico e uma visualização complementar (vídeo abaixo).

https://github.com/user-attachments/assets/025dacbf-e23c-4ba2-8ba9-189cdf322f8e

