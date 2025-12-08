# e2e

## Getting started

Install dependencies with `poetry`:

```bash
poetry install
```

## Running tests

1. Make sure the other applications in this repository are running
2. Run all test:

    ```bash
    poetry run pytest
    ```

3. Run all tests with a interactive user interface

    ```bash
    PWDEBUG=1 poetry run pytest --headed
    ```

4. Open interface for generating new tests

    ```bash
    poetry run python -m playwright codegen localhost:5173
    ```