# Projeto 1 - Análise de Vendas

Este projeto tem como objetivo analisar os dados de vendas de uma empresa fictícia para identificar as principais tendências e oportunidades de mercado.

## Objetivos

- Analisar o desempenho de vendas ao longo do ano.
- Identificar os produtos mais vendidos.
- Sugerir estratégias de marketing com base nos dados.

## Tecnologias Utilizadas

- **Power BI**: Para criação de dashboards interativos
- **Power Query**: Para transformação dos dados e utilização do editor avançado (M language), para adição de colunas e renomeação
- **Excel**: Para manipulação inicial dos dados

## Passo a Passo

### 1. Coleta de Dados
- Os dados com dados fictícios foram gerados com a ajuda do ChatGPT .
- O arquivo CSV contém informações como: `Data da Venda`, `Produto`, `Quantidade`, `Valor`, `Estado`, `Categoria`.

### 2. Limpeza e Preparação dos Dados
- Remoção de valores nulos e duplicados.
- Correção de dados inconsistentes
- Conversão de tipos de dados (datas, números, etc.).
- Criação de colunas adicionais, como `Receita Total` (calculada multiplicando `Quantidade` por `Valor`).

### 3. Análise Exploratória
- Criação de gráficos de barras para visualizar os produtos mais vendidos por categoria.
- Criação de gráficos de linha para visualizar a quantidade e o valor total vendido por categoria.
- Uso da segmentação de dados para selecionar a data desejada.
- Uso de cartão para mostrar valor total e ticket médio.

### 4. Criação do Dashboard
- Importação dos dados para o Power BI.
- Transformação dos dados com Power Query e M Language.
- Criação de medidas DAX necessárias para a visualização.
- Criação de visualizações dinâmicas para monitorar o desempenho de vendas.


### 5. Conclusão
- A categoria com mais produtos vendidos é a 'Eletrônicos'.
- A categoria com maior valor é a 'Roupas.
- O estado com maior quantidade de vendas é o Rio de Janeiro.

## Próximos Passos

- Implementar um modelo preditivo para prever vendas futuras.
- Expandir a análise para incluir dados de clientes.



