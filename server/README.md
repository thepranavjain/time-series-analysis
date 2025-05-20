# time-series-analysis server

## Pre-requisites 
- Make sure you have uv installed [https://docs.astral.sh/uv/](https://docs.astral.sh/uv/)
- Run this to install deps -
```sh
uv sync -p 3.12
```

## Run in dev mode
```sh
uv run fastapi dev main.py
```

## Run in production mode
```sh
uv run fastapi run main.py
```
