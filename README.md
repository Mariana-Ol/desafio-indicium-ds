# Projeto de análise exploratória e previsão de notas IMDB

## Descrição do projeto

Este projeto utiliza um dataset de filmes do IMDB para analisar as características que mais influenciam a nota de um filme. O objetivo final é construir um modelo de Machine Learning capaz de prever a `IMDB_Rating` com base em features como gênero, ano de lançamento, nota da crítica (Meta score) etc.

O modelo final escolhido foi um **Random Forest Regressor**, que apresentou um Mean Absolute Error (MAE) final de aproximadamente **0.1468** no conjunto de teste.

---

## Como Instalar e Executar o Projeto

Siga os passos abaixo para configurar o ambiente e executar a análise.

### Pré-requisitos

- Python 3.8 ou superior
- Pip (gerenciador de pacotes do Python)

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Mariana-Ol/desafio-indicium-ds.git
    cd Desafio Indicium
    ```


2.  **Instale as dependências:**
    O arquivo `requirements.txt` contém todos os pacotes necessários. Para instalá-los, execute:
    ```bash
    pip install -r requirements.txt
    ```

---

## Como Executar

A análise completa, desde a exploração dos dados (EDA) até a modelagem e avaliação, está contida no Jupyter Notebook `EDA_e_modelagem_Filmes.ipynb`.

1.  Inicie o Jupyter Notebook ou Jupyter Lab:
    ```bash
    jupyter notebook
    ```
2.  Abra o arquivo `EDA_e_modelagem_Filmes.ipynb`.
3.  Execute as células do notebook em ordem sequencial para reproduzir toda a análise e o treinamento do modelo.

---

## Estrutura do Repositório

-   `README.md`: Este arquivo, com as instruções do projeto.
-   `requirements.txt`: Lista de pacotes e versões para a instalação.
-   `EDA_e_modelagem_Filmes.ipynb`: Jupyter Notebook com toda a análise exploratória, pré-processamento e códigos de modelagem.
-   `model_random_forest.pkl`): O modelo final treinado.