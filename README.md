# Configuración de Python para Análisis de Datos Ambientales

## Descripción
Este proyecto trabaja con datos meteorológicos de SENAMHI en formato Excel usando Python y Visual Studio Code.

## Requisitos previos

### Software necesario
- **Visual Studio Code** - [Descargar aquí](https://code.visualstudio.com)
- **Python** (última versión) - [Descargar aquí](https://www.python.org/downloads/)
- **Git** (opcional)

### Extensiones de VS Code
Instalar las siguientes extensiones desde el Marketplace de VS Code:

1. **Jupyter** - Extensión principal para trabajar con notebooks `.ipynb`
2. **Python** - Extensión oficial de Microsoft
3. **Excel Viewer** - Para visualizar archivos Excel
4. **Edit CSV** - Para editar archivos CSV
5. **Code Runner** (opcional) - Añade el botón "play" para ejecutar código

## Instalación de librerías

### Instalación completa (recomendada)
```bash
py -m pip install pandas matplotlib openpyxl
```

### Instalación individual
```bash
python -m pip install pandas
python -m pip install matplotlib
python -m pip install openpyxl
```

### Verificar instalación
```bash
python --version
```

## Fuente de datos

- **SENAMHI** - [Portal de estaciones](https://www.senamhi.gob.pe/?p=estaciones)
- Datos meteorológicos disponibles desde 2020
- Archivos en formato Excel (.xlsx)

## Estructura del proyecto

```
proyecto/
│
├── README.md
├── [archivo_excel_senamhi].xlsx
└── analisis.ipynb
```

**Nota:** Todos los archivos deben estar en el mismo nivel (misma carpeta) para evitar problemas de rutas.

## Comandos útiles

### Terminal en VS Code
- `Ctrl + Ñ` - Abrir/cerrar terminal
- `clear` - Limpiar terminal
- `python --version` - Verificar versión de Python instalada

### Ejecutar código
- **Run All** - Ejecutar todas las celdas del notebook
- **Run Cell** - Ejecutar celda individual (botón ▶️ o Shift + Enter)

## Solución de problemas comunes

### Error: "No module named 'pandas'"
```bash
python -m pip install pandas
```

### No aparece el triángulo de "play"
- Instalar extensiones **Jupyter** y **Code Runner**
- Reiniciar VS Code

### Error al leer archivos Excel
```bash
py -m pip install openpyxl
```

### Actualizar pip (si es necesario)
```bash
python -m pip install --upgrade pip
```

## Tipo de archivos

- **`.ipynb`** - Jupyter Notebooks (recomendado para análisis interactivo)
- **`.py`** - Scripts de Python tradicionales
- **`.xlsx`** - Archivos de datos de SENAMHI

## Notas adicionales

- Los notebooks `.ipynb` permiten fragmentar el código y son más amigables para análisis exploratorio
- Mantener la estructura de carpetas organizada para evitar problemas de rutas
- Los datos de SENAMHI pueden requerir correcciones previas al análisis

## Soporte

Para dudas sobre:
- **SENAMHI**: [www.senamhi.gob.pe](https://www.senamhi.gob.pe)
- **Python**: [Documentación oficial](https://docs.python.org)
- **VS Code**: [Documentación oficial](https://code.visualstudio.com/docs)