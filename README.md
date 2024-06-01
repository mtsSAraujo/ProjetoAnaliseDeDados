# Projeto: Análise de Expectativa de Vida

Este repositório contém arquivos e códigos utilizados para a análise de dados de expectativa de vida. O objetivo principal é tratar os dados, realizar análises estatísticas e previsões futuras, bem como disponibilizar os dados tratados para visualização em ferramentas de BI, como o Power BI.

## Arquivos no Repositório

### 1. life_expectancy.csv
- **Descrição:** Arquivo com os dados brutos de expectativa de vida baixados do site "Kaggle".
- **Conteúdo:** Este arquivo contém dados sem qualquer tratamento prévio, diretamente extraídos da fonte.
- **Fonte:** Kaggle

### 2. economicBackground.ipynb
- **Descrição:** Código Python (notebook Jupyter) responsável pelo tratamento dos dados do arquivo `life_expectancy.csv`.
- **Funcionalidades:**
  - Exclusão de colunas irrelevantes.
  - Tratamento de dados nulos.
  - Download do arquivo tratado para análises futuras e visualizações no Power BI.
- **Uso:** Executar este notebook para gerar o arquivo `economicBackground.xlsx` com os dados tratados.

### 3. economicBackground.xlsx
- **Descrição:** Arquivo Excel contendo os dados do `life_expectancy.csv` após o tratamento realizado pelo código Python `economicBackground.ipynb`.
- **Conteúdo:** Dados limpos e prontos para análises estatísticas e visualizações.

### 4. Analise Dos Dados (Previsão Futura).ipynb
- **Descrição:** Código Python (notebook Jupyter) utilizado para realizar análises futuras dos valores de expectativa de vida.
- **Funcionalidades:**
  - Análise da curvatura normal.
  - Cálculo de curtose e assimetria.
  - Cálculo de medidas estatísticas (média, moda, mediana, quartis, etc.).
  - Plotagem de gráficos relevantes para visualização das análises.
- **Uso:** Executar este notebook para obter insights estatísticos e previsões futuras com base nos dados tratados.

## Como Usar

1. **Tratamento dos Dados:**
   - Execute o notebook `economicBackground.ipynb` para tratar os dados do arquivo `life_expectancy.csv`.
   - O notebook gerará o arquivo `economicBackground.xlsx` com os dados tratados.

2. **Análises e Previsões:**
   - Utilize o arquivo `economicBackground.xlsx` como entrada para o notebook `Analise Dos Dados (Previsão Futura).ipynb`.
   - Execute o notebook `Analise Dos Dados (Previsão Futura).ipynb` para realizar as análises estatísticas e previsões.

## Requisitos

- Python 3.x
- Bibliotecas Python:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy
  - jupyter

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.


---

Se você tiver alguma dúvida ou precisar de assistência, não hesite em entrar em contato. Aproveite a análise e as previsões de dados de expectativa de vida!
