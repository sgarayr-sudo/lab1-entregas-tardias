# Nombre del repositorio

Repositorio individual de analítica. Separa datos, experimentos, código reutilizable y resultados.

## Estructura

```
data/
  raw/          # datos originales, no se publican
  processed/    # datos preparados, se regeneran
notebooks/      # análisis en .ipynb
src/            # funciones reutilizables de siguientes retos
reports/
  S12_resultados_ID_01.json
README.md
```

## Cómo usarlo

1. Coloca los datos originales en `data/raw/` (están ignorados por Git).
2. Ejecuta el notebook en `notebooks/`; los datos preparados se guardan en `data/processed/`.
3. Guarda los resultados en `reports/S12_resultados_ID_01.json`.
