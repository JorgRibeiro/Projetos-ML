# Projetos-ML

## Como rodar o projeto

### Pré-requisitos
- Python 3.12+
- uv (gerenciador de ambientes e pacotes) 
- Jupyter Lab

### Configuração de ambiente
1. Clone esse repositório

2. Crie um ambiente virtual isolado:

    ```
    uv venv --python 3.12 .venv     # Para criar o ambiente
    source .venv/bin/active.fish   # Para fish 
    ```

3. Instale as dependêcias

    ```
    uv pip install -r requirements.txt
    ```

4. Extraia o dataset

    ```
    unzip house-prices-advanced-regression-techniques.zip -d datasets/house-prices
    ```

5. Selecione o kernel correto no jupyter
