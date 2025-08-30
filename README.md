# API Regression Tests

This project contains automated regression tests for a sample API, written in Python using `pytest`.

## Setup

1.  **Create and activate a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

**Note:** If you need to recreate the virtual environment, you can remove the `venv` directory and follow the setup steps again:
```bash
rm -rf venv
```

## Running Tests

*   **Run all tests:**
    ```bash
    ./venv/bin/pytest
    ```

*   **Run tests in parallel:**
    ```bash
    ./venv/bin/pytest -n auto
    ```

*   **Run tests in parallel with report:**
    ```bash
    ./venv/bin/pytest -n auto --tb=short --html=report.html
    ```

## Project Structure

```
.
├── requirements.txt
├── tests/
└── config.ini
```