# sample Poetry project to run pytest


## files

```
├── README.md
├── hello
│   ├── __init__.py
│   ├── hello.py
│   └── main.py
├── poetry.lock
├── pyproject.toml
└── tests
    └── test_hello.py
```

## run unit test

```bash
poetry run pytest -v
```

## run the project scipt

```
poetry run hello
```
