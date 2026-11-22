# Datos originales

No se publica una copia de la base original porque contiene fecha de nacimiento exacta, tipo de identificación
y lugar de expedición del documento. Los cuadernos la descargan directamente de la fuente:

- Fuente: Universidad Pedagógica y Tecnológica de Colombia (2025). *Deserción académica pregrado y posgrado*
  [Conjunto de datos]. Portal de Datos Abiertos de Colombia. https://www.datos.gov.co/d/3iew-7wpx
- Licencia: Creative Commons Atribución-CompartirIgual 4.0 (CC BY-SA 4.0).
- Tamaño al 20 de noviembre de 2026: 3.372 registros y 13 columnas.

```python
import pandas as pd
crudo = pd.read_csv("https://www.datos.gov.co/resource/3iew-7wpx.csv?$limit=10000", dtype=str)
```
