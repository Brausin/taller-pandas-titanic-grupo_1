# /src (opcional — código reutilizable)

Si el equipo quiere, puede crear módulos `.py` para no repetir código en los notebooks.

- **Ejemplos útiles** (opcionales):
  - `cargue_datos.py` → lectura de `train.csv` y `test.csv` (punto 1), unión con `source` (punto 5).
  - `ingenieria_variables.py` → `Familiares = SibSp + Parch` (punto 4) y `grupo_etario` (punto 11).
  - `analisis_basico.py` → `describe()` y comparaciones (punto 3).
  - `limpieza.py` → faltantes y visualización de nulos (punto 7).
  - `agrupaciones.py` → groupby/agg/contingencias para hipótesis (punto 9), distribución de `Cabin` (punto 10).
  - `visualizaciones.py` → gráficos (punto 12).

**Puntos relacionados**: 4–12.
