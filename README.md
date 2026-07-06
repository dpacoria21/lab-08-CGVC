# Laboratorio 08 - CGVC

Solucion del laboratorio de procesamiento de imagenes con Python, OpenCV, NumPy y Matplotlib.

## Entorno Conda

Conda instalado en esta maquina:

```powershell
C:\Users\diego\anaconda3\Scripts\conda.exe --version
```

Crear el entorno:

```powershell
C:\Users\diego\anaconda3\Scripts\conda.exe env create -f environment.yml
```

Si el entorno ya existe, actualizarlo:

```powershell
C:\Users\diego\anaconda3\Scripts\conda.exe env update -n lab08-cgvc -f environment.yml --prune
```

Registrar el kernel de Jupyter:

```powershell
C:\Users\diego\anaconda3\Scripts\conda.exe run -n lab08-cgvc python -m ipykernel install --user --name lab08-cgvc --display-name "Python (lab08-cgvc)"
```

Ejecutar el notebook:

```powershell
C:\Users\diego\anaconda3\Scripts\conda.exe run -n lab08-cgvc jupyter nbconvert --to notebook --execute notebooks\Laboratorio_08_Procesamiento_Imagenes.ipynb --inplace
```

## Archivos

- `notebooks/Laboratorio_08_Procesamiento_Imagenes.ipynb`: notebook resuelto y ejecutado.
- `data/`: imagenes base generadas por el notebook.
- `resultados/`: imagenes resultantes de cada ejercicio.
- `capturas/`: capturas usadas en el informe.
- `Laboratorio_0x_Pacori_Anccasi_Diego_UNSA_ CGVCM.docx`: informe completado.
