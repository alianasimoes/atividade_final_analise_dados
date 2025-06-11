# 📊 Análise de Dados de Saneamento no Brasil – SNIS

Este repositório apresenta uma análise baseada na base de dados do **Sistema Nacional de Informações sobre Saneamento (SNIS)**, com foco na cobertura de água potável e esgotamento sanitário nas áreas urbanas dos estados brasileiros, ao longo dos últimos cinco anos. A análise busca também identificar possíveis relações entre saneamento básico e indicadores de saúde pública.

Trabalho realizado para o Ciclo Formativo Preta Labs em Inteligência Artificial
Participantes: Aliana Simões, Fernanda Brito, Gabrielle, Izaura Souza, Karla Oliveira, Mariana, Thaís

## 🧩 Introdução

A base do SNIS foi escolhida por sua:

* **Abrangência nacional**
* **Periodicidade confiável**
* **Detalhamento dos dados**

Essa fonte permite uma visão ampla e atualizada sobre o acesso aos serviços essenciais de saneamento no Brasil. Além disso, os dados disponíveis são valiosos para cruzamentos com informações de saúde pública, viabilizando investigações sobre a relação entre infraestrutura sanitária e incidência de doenças.

## 🛠️ Metodologia

A análise foi realizada seguindo um processo estruturado para garantir **clareza**, **organização** e **reprodutibilidade**. As principais etapas foram:

1. **Definição das perguntas norteadoras**
   Elaboração de questões específicas para guiar a investigação e delimitar o escopo da análise.

2. **Ambiente de trabalho no Google Colab**
   Utilização do ambiente colaborativo para facilitar o desenvolvimento e compartilhamento da análise.

3. **Instalação das bibliotecas necessárias**
   Carregamento de bibliotecas Python voltadas para análise de dados, como: 
    Bibliotecas de análise:
    import pandas as pd
    import numpy as np

    Bibliotecas para produção de gráficos:
    import seaborn as sns
    import matplotlib.pyplot as plt
    import matplotlib.ticker as ticker

    Biblioteca para supressão de warnings:
    import warnings
    
    Biblioteca para acesso à base de dados:
    import basedosdados as bd

    Configuração de bibliotecas:
    warnings.filterwarnings("ignore")
    sns.set_theme(style = "whitegrid")

4. **Leitura e tratamento dos dados**

   * Correção de inconsistências
   * Seleção de colunas relevantes
   * Estruturação dos dados em formatos apropriados para análise

5. **Geração de gráficos e visualizações**
   Criação de representações visuais para explorar e comunicar os resultados obtidos.

## 📂 Fonte dos Dados

Os dados utilizados neste projeto foram extraídos do portal oficial do **Sistema Nacional de Informações sobre Saneamento (SNIS)**:

> 🔗 [https://www.gov.br/snis/](https://www.gov.br/snis/)

## 📈 Exemplos de Indicadores Analisados

* Qual é a cobertura de acesso à água potável e esgotamento sanitário nos estados brasileiros nos últimos 5 anos?
* Qual a natureza jurídica mais recorrente por estado?
* Qual a tendência observada no investimento público em saneamento básico, no âmbito estadual, ao longo desses últimos 5 anos?
* Como os indicadores de saneamento se correlacionam com índices de saúde (ex.: incidência de doenças)?


## 🚀 Como Executar

Passos para configurar o projeto:

1. Acesse o link: https://console.cloud.google.com/projectselector2/home/dashboard
2. Aceite o Termo de Serviços do Google Cloud
3. Clique em Create Project/Criar Projeto
4. Escolha um nome bacana para o seu projeto :)
5. Clique em Create/Criar

## 🤝 Contribuições

Sinta-se à vontade para abrir *issues*, propor melhorias ou enviar *pull requests*. Este é um projeto aberto e colaborativo!

