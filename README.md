# Análisis de Pingüinos

Proyecto de ciencia de datos para el análisis de un conjunto de datos sobre pingüinos.
Este repositorio incluye el entorno de desarrollo configurado y reproducible para todo el equipo.

## Requisitos previos

- **Python 3.12** (recomendado; el entorno fue creado con Python 3.12.10)
- Windows, macOS o Linux

## Estructura del proyecto

```
analisis_pinguinos/
├── .venv/              # Entorno virtual (no subir a control de versiones)
├── requirements.txt    # Librerías y dependencias con versiones fijadas
├── analisis.py         # Script principal de análisis
└── README.md           # Este archivo
```

## Configuración del entorno

### 1. Crear el entorno virtual

Desde la carpeta del proyecto (`analisis_pinguinos/`):

```bash
python -m venv .venv
```

### 2. Activar el entorno virtual

**Windows (PowerShell):**

```powershell
.\.venv\Scripts\Activate.ps1
```

> Si PowerShell bloquea la ejecución del script, ejecuta primero:
> `Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process -Force`

**Windows (CMD):**

```cmd
.\.venv\Scripts\activate.bat
```

**macOS / Linux:**

```bash
source .venv/bin/activate
```

Cuando el entorno está activo, verás `(.venv)` al inicio de la línea de comandos.

### 3. Instalar las dependencias

Con el entorno activado:

```bash
pip install -r requirements.txt
```

Esto instala `pandas`, `matplotlib`, `seaborn` y todas sus dependencias con las
versiones exactas fijadas en `requirements.txt`, garantizando que todos los miembros
del equipo trabajen con el mismo entorno.

## Librerías instaladas

- **pandas** — manipulación y análisis de datos
- **matplotlib** — visualización de datos
- **seaborn** — visualizaciones estadísticas

## Uso

Con el entorno activado, ejecuta el script de análisis:

```bash
python analisis.py
```

## Desactivar el entorno virtual

```bash
deactivate
```
