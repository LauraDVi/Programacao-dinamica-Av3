# FIAP — Dynamic Programming | Checkpoint 2

## Integrantes do grupo
- Raphael Aaron - 564067
- Felipe Catto - 562106
- Kimberly Kristina - 564080
- Laura Dantas - 564064

## Disciplina
**FIAP — Dynamic Programming**  
**Checkpoint 3 — Em Grupo**  
Professor: Andre Marques

## Estrutura do Repositório

```
Checkpoint_2_em_grupo/
├── notebook.ipynb          ← Notebook principal executado
└── README.md               ← Este arquivo
```

## Sobre o Projeto

Sistema de rotas de metrô para 3 metrópoles usando Programação Dinâmica:

| Cidade | Origem | Destino | Estações |
|--------|--------|---------|----------|
| 🇧🇷 São Paulo | Tucuruvi (L1) | Capão Redondo (L5) | 40+ |
| 🇨🇳 Beijing | Sihui East (L1) | Xizhimen (L2/L4) | 35+ |
| 🇺🇸 San Francisco | Dublin/Pleasanton | Daly City | 35+ |

## Tecnologias

- Python 3.10+
- `functools.lru_cache` — memoização
- `tracemalloc` + `time` — análise de desempenho  
- `folium` — visualização em mapa real
- `matplotlib` — gráficos comparativos

## Como Executar

```bash
pip install folium matplotlib networkx
jupyter notebook notebook.ipynb
```
