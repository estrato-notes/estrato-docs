# Documentação Estrato - Instruções

## Pré-requisitos

- Python 3.x
- pip

### Setup

1. **Clonar o repositório:**

    ```bash
    git clone https://github.com/andre-maia51/tppe-estrato-docs.git
    cd tppe-estrato-docs
    ```

2. **Criar e ativar ambiente virtual:**

    ```bash
    # Criar
    python -m venv .venv

    # Ativar (Linux/macOS)
    source .venv/bin/activate

    # Ativar (Windows)
    .\.venv\Scripts\activate
    ```

3. **Instalar dependências:**

    ```bash
    pip install mkdocs mkdocs-material
    ```

### Execução

1. **Iniciar servidor local:**

    ```bash
    mkdocs serve
    ```

2. **Acessar o site:**

    Abra o navegador em `http://127.0.0.1:8000`
