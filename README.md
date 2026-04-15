# 🚲 Dashboard de Aluguel de Bicicletas

Este projeto consiste no desenvolvimento de um dashboard interativo no **Power BI** para análise de dados de aluguel de bicicletas, utilizando o dataset **Bike Sharing Dataset**.  
O objetivo é transformar os dados em informações visuais claras e úteis, facilitando a identificação de padrões, tendências e comportamentos dos usuários ao longo do tempo.

---

## 📌 Objetivo do Projeto

O dashboard foi criado com a finalidade de analisar o comportamento dos aluguéis de bicicletas considerando diferentes fatores, como:

- volume total de aluguéis;
- comparação entre usuários casuais e registrados;
- distribuição dos aluguéis ao longo dos anos;
- análise dos meses com maior movimentação;
- identificação de horários de pico;
- influência de clima, temperatura e umidade na demanda.

---

## 🛠 Ferramentas Utilizadas

- **Power BI** — criação do dashboard interativo;
- **Python** — apoio no pré-processamento e organização dos dados;
- **Pandas** — limpeza e manipulação do dataset;
- **Kaggle Dataset** — fonte dos dados utilizados.

---

## 📂 Dataset Utilizado

O projeto foi desenvolvido com base no dataset **Bike Sharing Dataset**, que contém informações sobre o sistema de compartilhamento de bicicletas, incluindo variáveis como:

- data;
- hora;
- estação do ano;
- clima;
- temperatura;
- umidade;
- velocidade do vento;
- quantidade de usuários casuais;
- quantidade de usuários registrados;
- total de aluguéis.

---

## 📊 Principais Análises do Dashboard

O dashboard foi organizado para permitir diferentes tipos de análise, como:

### 1. Visão Geral
- total de aluguéis;
- comparação entre anos;
- evolução da demanda ao longo do tempo.

### 2. Perfil dos Usuários
- comparação entre **usuários casuais** e **usuários registrados**;
- identificação do grupo com maior participação no sistema.

### 3. Análise Temporal
- comportamento dos aluguéis por:
  - ano;
  - mês;
  - hora;
- identificação dos horários de pico.

### 4. Influência Climática
- relação entre o total de aluguéis e fatores ambientais, como:
  - clima;
  - temperatura;
  - umidade;

---

## 🎯 Insights Esperados

Com o dashboard, é possível obter insights como:

- quais anos apresentaram maior volume de aluguéis;
- quais meses concentram mais uso;
- em quais horários ocorre maior demanda;
- se usuários registrados utilizam mais o serviço do que usuários casuais;
- de que forma o clima influencia o comportamento dos aluguéis.

---

## 🧹 Tratamento dos Dados

Durante o desenvolvimento, alguns ajustes foram realizados no dataset, como:

- remoção de colunas desnecessárias, como `instant` `Ano` `Mês`;
- organização de colunas de data;
- preparação de campos para melhor uso no Power BI;
- ajustes para filtros por ano, mês e demais variáveis analíticas.

---

## 📸 Estrutura do Dashboard

O dashboard foi planejado para ser interativo e intuitivo, com:

- filtros por ano;
- navegação entre páginas;
- gráficos de colunas, linhas e cartões;
- destaque visual para os principais indicadores;
- análise separada por tema, como visão geral, clima e horários de pico.

---

## ▶️ Como Visualizar

1. Utilize o link presente no github para visualização facilitada;
2. Explore os filtros e as páginas do dashboard.
