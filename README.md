# Comparación urbana: ciudades griegas y romanas

Este proyecto genera una lámina comparativa entre la `polis` griega y la ciudad romana, combinando:

- implantación territorial,
- relaciones institucionales,
- glosario visual,
- y una explicación en `Markdown`.

## Archivos

- `generar_grafo.py`: genera la imagen principal.
- `comparacion_ciudades_griegas_romanas.png`: salida gráfica.
- `diferencias_ciudades_griegas_romanas.md`: explicación conceptual y glosario.
- `requirements.txt`: dependencias Python.

## Uso rápido

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python generar_grafo.py
```

## Nota sobre VS Code

Si Pylance marca `matplotlib`, `networkx` o `numpy` como no resueltos, selecciona el intérprete de `.venv` en VS Code.
