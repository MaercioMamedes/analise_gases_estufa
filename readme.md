# Análise de Dados de Emissões de Gases de Efeito Estufa no Brasil 1970-2021
## Aplicando técnicas de Data Science com Python

### Descrição

Este repositório contém atividades e desafios resolvidos durante o curso [**Pandas: selecionando e agrupando dados**](https://cursos.alura.com.br/course/pandas-selecao-agrupamento-dados) da plataforma de cursos online [Alura](https://www.alura.com.br/).

Para esse curso foi utilizado a base de dados  do [SEEG - Sistema de Estimativa de Emissões e Remoções de Gases de Efeito Estufa](https://seeg.eco.br/). Os arquivos utilizados encontram-se no diretório `dados` na raiz do projeto.

Atividades desenvolvidas, foram agrupadas de acordo com as unidades do curso e divididas nos tópicos de estudo do curso, cada unidade tem um arquivo `jupyter notebook` relacionado.

### Estrutura do Projeto

* #### Unidade I - conhecendo os dados
    - Importar dados de abas de arquivo excel no pandas.
    - Encontrar valores únicos de uma coluna do DataFrame com o método unique().
    - Filtrar dados com seleção booleana.
    - Remover colunas de uma tabela com o método drop().
* #### Unidade II - agrupamento de dados
    - Fazer a transformação de dados do formato wide para long.
    - Entender as diferenças entre um DataFrame no formato wide e long.
    - Construir agrupamentos de dados com o método groupby.
    - Visualizar grupos gerados pelo groupby e usar métodos de agregação.
    - Construir gráficos de barras usando o método plot.
* #### Unidade III - agrupamento multi-index
    - Construir agrupamentos a partir de mais de uma informação simultaneamente.
    - Selecionar dados em DataFrames multi index.
    - Alterar posição dos níveis hierárquicos dos índices em um DataFrame.
    - Selecionar índices onde o valor for máximo com o método idxmax().
    - Construir tabelas de pivô com o método pivot_table().
    - Criar múltiplos gráficos a partir de um DataFrame com várias colunas usando subplots.
* #### Unidade IV - unindo dados
    - Filtrar valores contendo parte de uma string em colunas de um DataFrame usando str.contains().
    - Criar colunas com base em dados de outras colunas usando o método assign().
    - Utilizar expressões regulares para buscar padrões textuais em strings.
    - Substituir parte de uma string em valores de uma coluna com método replace().
    - Unir conjuntos de dados com o método merge().
    - Construir gráficos de barras e dispersão interativos com a biblioteca plotly.

## Pré-requisitos

* **Python:** Recomenda-se ter o interpretador Python  [Anaconda](https://www.anaconda.com/) instalado.
* **Ambiente virtual:**
* **Editor de código:** Escolha um editor de sua preferência, como o Visual Studio Code, PyCharm ou Jupyter Notebook.

## Building

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/MaercioMamedes/analise_gases_estufa.git
2. **Crie um ambiente virutal e ative-o**:  
    É altamente recomendado criar um [ambiente virtual](https://www.alura.com.br/artigos/ambientes-virtuais-em-python) para gerenciar as dependências do projeto.
3. ***Instale as dependências do Projeto***
    ```bash
    pip install -r requirements.txt
4. ***Baixe a base de dados do SEE e mova para a pasta `dados`***:
    [Dados de emissão de Gases](https://cdn3.gnarususercontent.com.br/2927-pandas-selecao-agrupamento-dados/1-SEEG10_GERAL-BR_UF_2022.10.27-FINAL-SITE.xlsx)
5. ***Abra o terminal da máquina e navegue até o diretório do projeto e execute o compando:***
    ```bash
    jupyter notebook