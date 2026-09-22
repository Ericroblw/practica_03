# Práctica 3: Python — Eric Robles

## Descripción
Resolución de los 20 ejercicios de la Práctica 3 sobre listas, funciones y paquetes, NumPy, diccionarios y pandas, lógica y control de flujo, y bucles.

## Entorno
- Python 3.12
- JupyterLab
- NumPy, pandas (ver `requirements.txt`)

## Estructura del repositorio
| Carpeta / Archivo | Contenido |
| --- | --- |
| `data/` | Ficheros CSV de partida (`ventas_retail.csv`, `empleados.csv`, `sensores_planta.csv`) |
| `notebooks/` | Notebook con la resolución completa (`practica3_python.ipynb`) |
| `src/` | Módulo de funciones auxiliares (`utilidades.py`) |
| `outputs/` | Ficheros generados durante la ejecución (`facturacion_por_region.csv`, `ingenieria_remoto_senior.csv`) |
| `requirements.txt` | Dependencias fijadas del proyecto |
| `.gitignore` | Archivos y carpetas excluidos del control de versiones |

## Cómo reproducir
```bash
# 1. Crear el entorno virtual con Python 3.12
py -3.12 -m venv .venv

# 2. Activar el entorno
.venv\Scripts\activate          # En Windows (CMD / PowerShell)
# source .venv/bin/activate     # En Linux / macOS

# 3. Instalar dependencias
pip install -r requirements.txt

# 4. Lanzar JupyterLab y abrir el notebook
jupyter lab notebooks/practica3_python.ipynb
