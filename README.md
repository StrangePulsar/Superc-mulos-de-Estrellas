# Análisis de Supercúmulos de Estrellas

## Descripción
Este proyecto modela la distribución espectral de energía (SED) de una región H II masiva. Las regiones H II son zonas ionizadas de gas que rodean estrellas jóvenes y calientes, donde el mecanismo de bremsstrahlung domina la emisión de radio. Además, se considera la emisión térmica de polvo en equilibrio con el gas.

### Objetivos
1. Modelar el SED combinando emisiones de gas ionizado y polvo.
2. Evaluar cómo los parámetros del gas (temperatura electrónica y medida de emisión) y del polvo afectan el espectro.
3. Comparar el modelo con observaciones de regiones H II ultra-compactas.

### Contenido del Notebook
- **Importación de librerías y configuración inicial:** Preparación del entorno de trabajo.
- **Modelado del SED:** Cálculo de la emisión de bremsstrahlung y del cuerpo gris.
- **Comparación con observaciones:** Validación del modelo con datos reales.
- **Variaciones en el SED:** Análisis de cómo los cambios en EM afectan el espectro.
- **Visualización de resultados:** Gráficos detallados para interpretar las diferencias en el SED.

### Instrucciones de Uso
1. **Requisitos previos:**
   - Python 3.8 o superior.
   - Dependencias: `numpy`, `matplotlib`, `scipy`.
2. **Ejecución:**
   - Abra el archivo `.ipynb` en un entorno compatible con Jupyter Notebook.
   - Ejecute las celdas en orden para generar los resultados.

### Resultados Esperados
- Un SED detallado que combine las emisiones del gas y del polvo.
- Gráficos que muestren la influencia de parámetros clave como EM y la temperatura.
- Comparaciones con estudios previos que refuercen la validez del modelo.

### Referencias
El análisis se basa en trabajos fundamentales como:
- Mezger & Henderson (1967): Modelos teóricos de emisión en regiones H II.
- Wood & Churchwell (1989): Estudio de regiones H II ultra-compactas.

### Créditos
Este proyecto fue desarrollado en el marco de la asignatura **AAF-431: Materia Interestelar**, en el tercer periodo académico del 2024.
