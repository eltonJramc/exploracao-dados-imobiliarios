# Análise de Dados Imobiliários

Este projeto realiza uma análise exploratória de dados do mercado imobiliário utilizando **Python** e a biblioteca **Pandas**. 
O objetivo é manipular, limpar, e visualizar dados relacionados a imóveis disponíveis para aluguel, além de gerar insights úteis sobre os tipos de imóveis, valores médios e distribuições.

## 🔍 Funcionalidades

- **Leitura e exploração inicial dos dados**: Exibição das primeiras e últimas linhas do dataset, colunas disponíveis, tipos de dados e informações básicas.
- **Estatísticas descritivas**: Cálculo de médias, agrupamentos e percentuais de diferentes tipos de imóveis.
- **Filtragem e limpeza de dados**: Remoção de registros inconsistentes, preenchimento de valores ausentes e criação de novas colunas.
- **Visualizações**: Geração de gráficos para analisar a distribuição e os preços médios por tipo de imóvel.
- **Exportação de dados tratados**: Salvamento do dataset limpo para arquivos CSV.

## 🛠️ Ferramentas e Tecnologias

- Linguagem: **Python**
- Biblioteca para manipulação de dados: **Pandas**
- Biblioteca para visualização: **Matplotlib**
- Ambiente de desenvolvimento: **Google Colab (Jupyter Notebook)**

## 📂 Estrutura do Código

1. **Importação de bibliotecas e leitura do dataset**:
   - O dataset foi importado diretamente de um repositório online e carregado no ambiente Python.

2. **Exploração dos dados**:
   - Análise básica da estrutura dos dados (`head`, `tail`, `info`, etc.).
   - Estatísticas descritivas e agrupamento de dados por tipo de imóvel.

3. **Limpeza e transformação dos dados**:
   - Remoção de registros com valores inconsistentes.
   - Criação de novas colunas, como `Valor_por_mes` e `Valor_por_ano`.
   - Geração de descrições textuais para os imóveis.

4. **Visualizações gráficas**:
   - Gráficos de barras horizontais para preços médios por tipo de imóvel.
   - Gráficos de barras para distribuição percentual de tipos de imóveis.

5. **Exportação do dataset tratado**:
   - Salvamento em formato CSV para facilitar análises futuras.

## 📊 Exemplos de Análises Realizadas

- **Preço médio por tipo de imóvel**
- **Análise da relação entre número de quartos e preço médio do aluguel**
- **Distribuição de valores do condomínio** 
