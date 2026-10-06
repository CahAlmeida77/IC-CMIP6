# Análise de Projeções Climáticas do CMIP6
Repositório desenvolvido no âmbito de uma **Iniciação Científica em Engenharia Ambiental**, reunindo os scripts em Python utilizados no processamento, análise estatística e visualização de dados climáticos provenientes de modelos globais do **Coupled Model Intercomparison Project Phase 6 (CMIP6)**.

O trabalho integra **projeções climáticas futuras e registros históricos de estações meteorológicas**, com foco na análise de variáveis de **precipitação e temperatura** e na avaliação da variabilidade entre diferentes modelos climáticos.

## Objetivo

Desenvolver uma rotina computacional para organizar, processar e analisar grandes volumes de dados climáticos, permitindo comparar diferentes modelos do CMIP6 e construir representações de **ensemble** para avaliar padrões, extremos e incertezas nas projeções climáticas.

## Metodologia computacional

Os códigos desenvolvidos contemplam etapas de:

* Leitura e processamento de arquivos climáticos no formato **NetCDF**;
* Extração de séries temporais a partir das coordenadas de estações meteorológicas;
* Organização e tratamento das séries históricas e projetadas;
* Cálculo de **máximos anuais de precipitação**;
* Processamento de diferentes modelos climáticos individualmente;
* Construção de **ensembles**, utilizando média e desvio-padrão entre os modelos;
* Geração de séries temporais e visualizações para comparação entre modelos;
* Consolidação dos resultados em arquivos **CSV** para análises posteriores.

## Estrutura do repositório

```text
iniciacao-cientifica/
│
├── Script
│   └── Processamento dos dados de precipitação,
│       cálculo de máximos anuais e ensemble
│
├── Temperatura_ensemble
│   └── Processamento e análise em ensemble
│       dos dados de temperatura
│
├── Temperatura_graficolinhas
│   └── Geração de séries e gráficos de temperatura
│
├── acumulada
│   └── Rotinas relacionadas à análise acumulada
│       das variáveis climáticas
│
├── estacoes.csv
│   └── Identificação e coordenadas das estações
│       meteorológicas utilizadas
│
└── LICENSE
```

## Tecnologias e bibliotecas

**Python** foi utilizado como principal linguagem para processamento e análise dos dados.

Principais bibliotecas empregadas:

* `pandas` — organização, tratamento e análise de dados;
* `numpy` — operações numéricas e processamento das séries;
* `netCDF4` — leitura e manipulação dos arquivos NetCDF;
* `matplotlib` — geração de gráficos e visualizações;
* `datetime` — tratamento das séries temporais.

## Aplicação na pesquisa

Os resultados obtidos por meio desses códigos fazem parte da análise de **projeções climáticas para a região de Sorocaba (SP) e municípios do entorno**, contribuindo para a investigação de possíveis alterações futuras nos padrões de precipitação e temperatura.
A utilização de múltiplos modelos climáticos permite evidenciar não apenas tendências e padrões médios, mas também a **variabilidade e a incerteza associadas às projeções**, aspecto fundamental para estudos de adaptação às mudanças climáticas e planejamento ambiental.

## Observação

Os scripts presentes neste repositório foram desenvolvidos e adaptados ao longo das diferentes etapas da pesquisa. Alguns caminhos de arquivos e diretórios utilizados originalmente são específicos do ambiente de desenvolvimento da pesquisa e, portanto, podem exigir ajustes para reprodução em outros computadores.
---
**Projeto de Iniciação Científica — Engenharia Ambiental | UNESP Sorocaba**
