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
- El dataset se carga con `plotly.express` (`px.data.gapminder()`), que retorna un `pandas.DataFrame`.

## Estructura
- `clustering.ipynb`: análisis, dendrogramas y visualizaciones (clusters/continentes).
- `pyproject.toml` y `poetry.lock`: dependencias y bloqueo (reproducibilidad).
- `.pre-commit-config.yaml`: calidad de código (Black, Ruff, nbQA para notebooks).
- `docs/clustering.html`: exportación del notebook con resultados embebidos.

## Calidad de código
- Formateo: Black
- Linter: Ruff
- Notebooks: nbQA (black/ruff)

## Exportar a HTML
```bash
poetry run jupyter nbconvert --to html --output-dir docs --output clustering.html clustering.ipynb
```

## Entrega
- Puedes comprimir el repositorio o publicar en GitHub.
- Nomenclatura sugerida: `JGA-TestDataScience-1.zip` o repo público con el mismo nombre.
