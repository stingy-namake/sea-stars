# 🌟 Catálogo de Estrelas Marinhas

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![R Version](https://img.shields.io/badge/R-%3E%3D%204.0-blue)](https://www.r-project.org/)
[![tidyverse](https://img.shields.io/badge/tidyverse-Included-orange)](https://www.tidyverse.org/)

Um pacote/complemento em R para catalogação, análise e visualização de dados de espécies de estrelas marinhas (Classe *Asteroidea*).

## 📋 Sobre o Projeto

Este repositório fornece ferramentas para pesquisadores, biólogos marinhos e entusiastas organizarem e analisarem dados de catalogação de estrelas marinhas. O sistema permite:

- Registro sistemático de espécimes
- Georreferenciamento de avistamentos
- Análises morfológicas e taxonômicas
- Visualização de distribuição geográfica
- Controle de dados de conservação

## 🚀 Funcionalidades

- ✅ **Cadastro de espécimes** - Registro completo com metadados
- ✅ **Classificação taxonômica** - Suporte a taxonomia integrada (Ordem, Família, Gênero, Espécie)
- ✅ **Georreferenciamento** - Integração com coordenadas geográficas
- ✅ **Análises estatísticas** - Funções para análise populacional
- ✅ **Visualização de dados** - Mapas de distribuição e gráficos morfológicos
- ✅ **Exportação de dados** - Formatos CSV, GeoJSON e Shapefile

## 📦 Pré-requisitos

```r
# Versão do R necessária
R >= 4.0.0

# Pacotes necessários
install.packages(c(
  "tidyverse",
  "sf",
  "leaflet",
  "shiny",
  "ggplot2",
  "dplyr",
  "DBI",
  "RSQLite"
))
