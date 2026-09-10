"""
===============================================================================
Mapeamento do Índice de Prioridade de Restauração (IPR) na Caatinga
-------------------------------------------------------------------------------
Autor: Thiago Costa Ferreira
Objetivo: Interpolação por Densidade de Kernel (KDE) com máscara espacial 
          do IBGE (geobr) para as parcelas do IFN.
===============================================================================
"""

# ipr-caatinga-restauracao
Pipeline de análise espacial (LISA, KDE) e modelagem preditiva (Random Forest) do Índice de Prioridade de Restauração (IPR) na Caatinga.

#Badge
# Análise Espacial da Prioridade de Restauração Florestal (IPR) na Caatinga
![Python Version](https://img.shields.io/badge/python-3.10%20%7C%203.11%20%7C%203.12-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Conclu%C3%ADdo-brightgreen)

Repositório oficial para processamento de dados, modelagem espacial e geração de mapas contínuos e de aglomeração espacial (LISA) do Índice de Prioridade de Restauração (IPR) na Caatinga, utilizando parcelas do Inventário Florestal Nacional (IFN).

## 📁 Estrutura do Repositório

- `scripts/`: Códigos em Python para geoprocessamento, KDE e análise de clusters LISA.
- `figures/`: Mapas em alta resolução padronizados na silhueta do bioma Caatinga.
- `requirements.txt`: Dependências e bibliotecas Python necessárias para reprodução do código.

## 🛠️ Tecnologias Utilizadas

- Python 3
- `geopandas` & `geobr` (Análise vetorial e malhas territoriais)
- `scipy` & `matplotlib` (Interpolação KDE e renderização cartográfica)

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/thiagoferreira1-bra/ipr-caatinga-restauracao.git](https://github.com/thiagoferreira1-bra/ipr-caatinga-restauracao.git)
