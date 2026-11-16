# ATD — MEGAF 2026/27 · Atividade de Fiabilidade

Material de apoio à atividade de Fiabilidade da unidade curricular de Análise e Transformação de Dados (Mestrado em Engenharia e Gestão de Ativos Físicos, ISEC).

## Por onde começar

1. Leia o enunciado e o documento base (pasta [`docs`](docs)).
2. Leia a Parte I do documento de apoio, com o Excel da aula aberto ao lado.
3. Faça o notebook comum (`00_comum`).
4. Passe ao capítulo e ao notebook do tema do seu grupo.

## Notebooks

Clique em "Abrir no Colab" para abrir o notebook no Google Colab (precisa de uma conta Google). No Colab, use *Ficheiro > Guardar uma cópia no Drive* para ficar com a sua versão.

| Pasta | O que mostra | |
|---|---|---|
| [Testes de ajustamento em Python (para todos os grupos)](00_comum) | Qui-quadrado passo a passo como no Excel da aula, classes de igual probabilidade, Kolmogorov–Smirnov, gráfico quantil–quantil e comparação das quatro distribuições. | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/00_comum/testes_de_ajustamento.ipynb) |
| [T1 — Taxa de falha e padrões de falha](T1_taxa_de_falha) | Taxa de falha empírica por classes, com os dados da aula; taxa de falha de um modelo. | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/T1_taxa_de_falha/T1_taxa_de_falha.ipynb) |
| [T2 — Estimação dos parâmetros da Weibull](T2_weibull) | Gráfico de Weibull (median ranks e regressão) e máxima verosimilhança, numa amostra dos dados da aula. | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/T2_weibull/T2_weibull.ipynb) |
| [T3 — Escolha da distribuição](T3_escolha_da_distribuicao) | Critério AIC e efeito de um modelo mal escolhido na fiabilidade prevista. Fazer primeiro o notebook comum. | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/T3_escolha_da_distribuicao/T3_escolha_da_distribuicao.ipynb) |
| [T4 — Dados censurados e Kaplan–Meier](T4_dados_censurados) | Kaplan–Meier à mão com oito unidades, erro de ignorar a censura e ajuste Weibull com censura (biblioteca lifelines). | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/T4_dados_censurados/T4_dados_censurados.ipynb) |
| [T5 — Sistemas reparáveis e disponibilidade](T5_sistemas_reparaveis) | MTBF, MTTR, disponibilidade, gráfico de falhas acumuladas e teste de Laplace, com duas máquinas inventadas. | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/T5_sistemas_reparaveis/T5_sistemas_reparaveis.ipynb) |
| [T6 — Diagramas de blocos](T6_diagramas_de_blocos) | Funções para série, paralelo e k-de-n, aplicadas a um sistema inventado. | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/T6_diagramas_de_blocos/T6_diagramas_de_blocos.ipynb) |
| [T7 — Componentes críticos e redundância](T7_componentes_criticos) | Importância de Birnbaum e comparação de alternativas de investimento, num sistema inventado. | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/T7_componentes_criticos/T7_componentes_criticos.ipynb) |
| [T8 — Simulação de Monte Carlo](T8_monte_carlo) | Simulação de um sistema de dois componentes, validação com a fórmula e intervalo de confiança. | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/T8_monte_carlo/T8_monte_carlo.ipynb) |
| [T9 — Otimização da manutenção preventiva](T9_manutencao_preventiva) | Custo por hora de uma política de substituição por idade, com uma peça e custos inventados. | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlavadodatasci/atd-megaf-fiabilidade/blob/main/T9_manutencao_preventiva/T9_manutencao_preventiva.ipynb) |

## Dados

| Ficheiro | Conteúdo |
|---|---|
| [`dados/tempo_falhas_aula.xlsx`](dados/tempo_falhas_aula.xlsx) | Excel resolvido na aula (tempos até à falha e teste de ajustamento) |
| [`dados/dados_fiabilidade.xlsx`](dados/dados_fiabilidade.xlsx) | Dados simulados da instalação, para o trabalho de grupo |

Os notebooks descarregam estes ficheiros automaticamente. Se a descarga falhar, o Colab pede o ficheiro: escolha-o no seu computador.

## Documentos

A pasta [`docs`](docs) tem o enunciado, o documento base e o documento de apoio.
