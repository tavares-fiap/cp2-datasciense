# Marvel vs DC: Análise Comparativa de Filmes e Séries
## Guilherme Rocha - RM97974 e Pedro Henrique - RM97877

Este repositório contém um projeto de análise de dados que compara os universos cinematográficos da Marvel e DC. O objetivo é explorar visualmente e estatisticamente as características de seus filmes e séries, avaliando aspectos como a distribuição de notas IMDb, o tipo de produção (filme ou série) e sua evolução ao longo dos anos.

## Visão Geral

Este projeto utiliza dados sobre filmes e séries da Marvel e DC para criar visualizações e gerar insights sobre as diferenças e semelhanças entre os dois universos. Um relatório interativo em HTML é gerado ao final, consolidando as análises realizadas.

## Objetivos do Projeto

- Quantificar e comparar o número de filmes e séries produzidos pela Marvel e DC.
- Comparar as avaliações do IMDb de filmes e séries entre os dois universos.
- Visualizar a evolução das notas IMDb ao longo dos anos.
- Gerar um relatório em HTML com todas as análises.

## Funcionalidades

- **Análises Estatísticas**: Resumo dos dados com contagem de registros, tipos de dados e dados faltantes.
- **Visualizações**: Gráficos comparativos para facilitar o entendimento das diferenças entre Marvel e DC.
- **Geração de Relatório HTML**: Um relatório consolidado e interativo para visualização e compartilhamento.

## Estrutura do Repositório

- `cp2_ds.ipynb`: O notebook Jupyter contendo todo o código de análise.
- `MarvelVsDC.csv`: Dataset com informações dos filmes e séries. ( Caso utilizar o COLAB favor colocar o arquivo .csv na pasta CONTENT)
- `templates/`: Pasta com templates para a geração do relatório HTML.
- `README.md`: Este arquivo de documentação.

## Tecnologias Utilizadas

- **Python**: Linguagem principal do projeto.
- **Pandas**: Para a manipulação e análise dos dados.
- **Seaborn** e **Matplotlib**: Para a criação de visualizações.
- **Jinja2**: Para a geração do relatório HTML.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado as seguintes dependências:

```bash
pip install pandas matplotlib seaborn jinja2
