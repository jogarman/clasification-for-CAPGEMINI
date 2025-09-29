# Clasification for CAPGEMINI

Análisis de clustering jerárquico (Gapminder 1952 vs 2007) con visualizaciones.

## Requisitos
- Python 3.9–3.13
- Poetry 2.x

## Instalación
```bash
poetry config virtualenvs.in-project true
poetry install
```

## Ejecutar el notebook
- Abre `clustering.ipynb` y ejecuta en orden desde el principio.

## Estructura
- `clustering.ipynb`: análisis, dendrogramas y visualizaciones (clusters/continentes).
- `pyproject.toml` y `poetry.lock`: dependencias y bloqueo (reproducibilidad).
- `.pre-commit-config.yaml`: calidad de código (Black, Ruff, nbQA para notebooks).
- `docs/clustering.html`: exportación del notebook con resultados embebidos.

## Calidad de código
- Formateo: Black
- Linter: Ruff
- Notebooks: nbQA (black/ruff)
