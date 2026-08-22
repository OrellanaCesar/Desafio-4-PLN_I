# Desafío 4 — PLN I

La entrega principal está en `Desafio_4.ipynb`. Implementa un traductor inglés-español Seq2Seq con LSTM, amplía el corpus a 30 000 pares, adapta las longitudes de secuencia y compara 128 contra 256 unidades recurrentes.

`Traductor.ipynb` contiene la versión base, útil para estudiar el flujo paso a paso.

## Ejecución

Con [uv](https://docs.astral.sh/uv/), desde la raíz del proyecto:

```bash
uv sync --group dev
uv run jupyter lab
```

Luego abrir `Desafio_4.ipynb` y ejecutar las celdas en orden.

- En Google Colab: abrir `Desafio_4.ipynb`, seleccionar acelerador GPU y ejecutar las celdas en orden.
- En local sin uv: crear un entorno de Python e instalar `tensorflow`, `numpy`, `pandas`, `matplotlib` y `nltk`. El corpus se descarga automáticamente en `data/` al ejecutar el notebook.

Los valores de las métricas y los cinco ejemplos de traducción se generan durante la ejecución para que sean reproducibles y no resultados escritos manualmente.
