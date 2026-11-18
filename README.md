# AlertaBairro — Data Science & Statistical Computing

Entregável da disciplina **Data Science & Statistical Computing** — GS CitizenTech 2026.2 (Engenharia de Software, FIAP).

## Integrantes

| Nome completo | RM |
|---|---|
| `[preencher]` | `[preencher]` |
| `[preencher]` | `[preencher]` |
| `[preencher]` | `[preencher]` |

## Arquivos

- `dados_ocorrencias_alertabairro.csv` — base de dados simulada de ocorrências urbanas (alagamentos, bueiros entupidos, deslizamentos) usada na análise.
- `analise_alertabairro.ipynb` — notebook com preparação dos dados, análise descritiva, visualizações e conclusões.

## Fonte dos dados

Base **simulada pela equipe** para fins didáticos do projeto, com padrões inspirados em boletins públicos de ocorrências urbanas e em dados pluviométricos de centros de monitoramento municipais (ex.: CGE-SP). Não contém dados pessoais reais. Os nomes de bairro usados são fictícios — a equipe deve substituí-los pela área real escolhida para o projeto (ver Ficha da CitizenTech) assim que possível.

## Como executar

1. Tenha Python 3 com `pandas`, `numpy` e `matplotlib` instalados (`pip install pandas numpy matplotlib`).
2. Mantenha o `.csv` na mesma pasta do notebook.
3. Abra `analise_alertabairro.ipynb` no Jupyter (`jupyter notebook`) ou no VS Code e rode todas as células (Run All).

## Perguntas de negócio respondidas

1. Quais bairros concentram mais ocorrências?
2. Qual o tipo de ocorrência mais recorrente?
3. Existe relação entre volume de chuva e gravidade da ocorrência?
4. Qual o tempo médio de resolução das ocorrências, e ele muda por gravidade?
