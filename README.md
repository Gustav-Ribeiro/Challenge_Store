# Análise de Dados – Alura Store Brasil

Este projeto apresenta uma análise completa das vendas da Alura Store Brasil, incluindo importação, tratamento, visualização e interpretação dos dados provenientes de quatro lojas distintas. Cada etapa do notebook é documentada abaixo.

---

## 1. Importação dos Dados

Na primeira etapa, são carregados os arquivos CSV contendo as informações de vendas de cada loja.

Atividades realizadas:
- Importação dos dados usando a biblioteca `pandas`
- Leitura dos arquivos via URLs
- Exibição das primeiras linhas das tabelas usando `head()`

---

## 2. Análise do Faturamento

Nesta etapa é avaliado o faturamento de cada loja.

Operações executadas:
- Seleção da coluna de preços
- Cálculo do total de vendas por loja
- Criação de gráfico de barras utilizando `matplotlib`
- Configuração de títulos, eixos e grade para melhor visualização

---

## 3. Vendas por Categoria

Os dados das quatro lojas são unificados para possibilitar a análise por categoria de produto.

Ações realizadas:
- Junção dos DataFrames com `pd.concat()`
- Agrupamento por categoria de produto
- Soma do valor total vendido em cada categoria
- Exibição dos resultados em tabela

---

## 4. Distribuição Percentual das Vendas

Um gráfico de pizza é construído para mostrar a participação percentual de cada categoria no total de vendas.

Inclui:
- Cálculo da proporção de vendas por categoria
- Plotagem com `matplotlib`
- Ajuste do aspecto visual para manter o formato circular

---

## 5. Produtos Mais Vendidos

Aqui são identificados os produtos com maior volume de vendas.

Processos:
- Agrupamento por nome do produto
- Soma das vendas totais
- Ordenação dos produtos mais vendidos
- Exibição dos resultados em tabela ou gráfico

---

## 6. Comparação entre Lojas

Os dados das quatro lojas são integrados para permitir análises comparativas.

Inclui:
- Consolidação das bases de dados
- Cálculo de métricas importantes
- Comparações entre desempenho das lojas

---

## 7. Visualizações Complementares

O notebook também inclui gráficos adicionais para:
- Observar tendências de vendas
- Comparar categorias
- Avaliar desempenho de produtos específicos

---
