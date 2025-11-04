# Heart Disease Prediction

## Estructura del proyecto
```text
/.
├─ .gitignore
├─ README.md
├─ requirements.txt
│
├─ data/
│  ├─ raw/                # Datos originales (no modificar) 
│  └─ processed/          # Datos limpios y listos para modelado
│
├─ notebooks/              # Notebooks (experimentos)
│
├─ src/                    # Código fuente (Código limpio y reutilizable)
│  
├─ models/                 # Modelos entrenados
│ 
└─ reports/
   └─ figures/             # Gráficos y visualizaciones
```

## Cómo empezar

Sigue estos pasos para configurar tu entorno de desarrollo local.

1. **Crea un entorno virtual**
    ```bash
    python -m venv .venv
    ```
3.  **Activa el entorno virtual:**
    * En **macOS/Linux**:
        ```bash
        source .venv/bin/activate
        ```
    * En **Windows** (PowerShell):
        ```bash
        .\.venv\Scripts\Activate
        ```
3.  **Instala las dependencias:**
    ```bash
    pip install -r requirements.txt
    ```



