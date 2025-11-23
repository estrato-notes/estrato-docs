# Estrato Documentation - Instructions

## Prerequisites

- Python 3.x
- pip

### Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/estrato-notes/estrato-docs.git
    cd estrato-docs
    ```

2. **Create and activate virtual environment:**

    ```bash
    # Create
    python -m venv .venv

    # Activate (Linux/macOS)
    source .venv/bin/activate

    # Activate (Windows)
    .\.venv\Scripts\activate
    ```

3. **Install dependencies:**

    ```bash
    pip install mkdocs mkdocs-material
    ```

### Running

1. **Start local server:**

    ```bash
    mkdocs serve
    ```

2. **Access the site:**

    Open your browser at `http://127.0.0.1:8000`