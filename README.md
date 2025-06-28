# 🏆 Premier League 24/25 — Análise com Business Intelligence ⚽

## 📘 Introdução

Este projeto foi desenvolvido como parte da disciplina **CSI605 – Sistemas de Apoio à Decisão** e tem como objetivo aplicar conceitos de **Business Intelligence (BI)** para analisar dados da temporada 2024/2025 da **Premier League**. Utilizando a ferramenta **Power BI**, foram extraídos e visualizados insights relevantes sobre jogadores, clubes e desempenho ao longo do campeonato. A análise visa demonstrar como o uso de BI pode transformar dados brutos em informações estratégicas para a tomada de decisão.

## 📂 Base de Dados

A base de dados utilizada para esta análise abrange múltiplas dimensões e fatos relacionados à Premier League 24/25. Os dados foram coletados e organizados de forma estruturada, contemplando as seguintes informações:

- 📊 Estatísticas individuais dos jogadores (gols, assistências, partidas disputadas, nacionalidade etc.)
- 🏟️ Informações dos clubes (nome, cidade, técnico, estádio)
- ⚔️ Confrontos e resultados entre os times
- 📈 Classificação geral da temporada
- 💰 Folhas salariais por jogador e por time
- 📚 Dados históricos e comparativos com temporadas anteriores (quando necessário)

## 🧩 Modelagem Multidimensional

Para a construção do modelo analítico, foi adotado o **modelo floco de neve (snowflake)**, que permite maior normalização das tabelas e melhor organização dos dados. A granularidade foi definida em dois níveis principais:

- **Por time**: para análises agregadas como desempenho coletivo, salários médios, confrontos entre clubes etc.
- **Por jogador**: para análises detalhadas de performance individual, contribuições em gols/assistências, comparativos salariais etc.

**Estrutura do modelo:**

- 🟨 **Tabelas Fato**:
  - Fato_JogadorEstatisticas
  - Fato_Confrontos
  - Fato_Salarios

- 🟦 **Tabelas Dimensão**:
  - Dim_Jogador
  - Dim_Clube
  - Dim_Temporada
  - Dim_Partida
  - Dim_Posicao
  - Dim_Nacionalidade

## 📊 Visualizações no Power BI

O dashboard desenvolvido no Power BI apresenta uma série de visualizações interativas, que permitem explorar os dados da Premier League 24/25 sob diversas perspectivas. As principais visualizações incluem:

- 🥅 **Ranking de Artilheiros e Assistentes**  
  Visualização dos líderes em gols e assistências, com filtros por clube e posição.

- 💸 **Ranking Salarial por Jogador e por Time**  
  Comparativo do investimento salarial dos clubes e dos maiores salários individuais.

- 🌍 **Diversidade de Nacionalidades**  
  Gráfico de distribuição por país de origem dos jogadores que atuaram na temporada.

- 📈 **Indicadores de Desempenho dos Clubes**  
  KPIs e gráficos com vitórias, empates, derrotas, gols marcados e sofridos.

## 💡 Principais Insights

A análise dos dados da Premier League 24/25 revelou uma série de descobertas relevantes:

- 🏆 **Liverpool foi o campeão da temporada**, mesmo apresentando uma folha salarial inferior à do Manchester City.
- ⚽ **Mohamed Salah** liderou tanto em **gols** quanto em **assistências**, sendo o jogador mais decisivo da competição.
- 🔥 Clubes com menor orçamento, como o Brighton, apresentaram desempenho superior ao esperado, evidenciando a eficiência técnica e tática.
- 🌎 Houve uma **alta diversidade de nacionalidades** entre os atletas, com destaque para jogadores africanos e sul-americanos.

## 🛠️ Tecnologias Utilizadas

- **Power BI**: Ferramenta de visualização e análise de dados
- **Modelagem Multidimensional**: Abordagem analítica com base em tabelas fato e dimensão
- **Base de Dados Estruturada**: Organização normalizada dos dados para eficiência e clareza

## 👤 Informações Adicionais

- **Aluno**: Vinícius Andrade Costa  
- **Curso**: Sistemas de Informação  
- **Disciplina**: CSI605 – Sistemas de Apoio à Decisão  
- **Link para o Dataset**: https://www.kaggle.com/datasets/flynn28/2025-premier-league-stats-matches-salaries

---

