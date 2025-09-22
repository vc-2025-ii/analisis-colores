# Instrucciones de la tarea

En esta tarea vas a trabajar con imágenes digitales para explorar conceptos básicos de procesamiento de imágenes: histogramas de color, manipulación pixel a pixel y conversión a escala de grises.

Tu repositorio debe contener **tres archivos obligatorios**:

* `utils.py`: Contiene las funciones implementadas.
* `demo.ipynb`: Notebook con ejemplos claros de uso de las funciones.
* `Readme.md`: Explicación del proceso seguido, resultados obtenidos y sección de **Nivel de uso de herramientas de inteligencia artificial** (instrucciones más abajo).

---

## Actividades a realizar

1. **Carga de una imagen**

   * Elige una imagen cualquiera (puede ser JPG o PNG).
   * Cárgala usando la librería PIL y conviertela a arreglo de Numpy.

2. **Cálculo de histogramas por canal de color**

   * Calcula los histogramas de la imagen original para cada canal (Rojo, Verde, Azul).
   * Muestra los histogramas de manera gráfica.

3. **Modificación de la imagen agregando una figura geométrica**

   * Agrega una figura geométrica básica (círculo, cuadrado, rectángulo, etc.) sobre la imagen.
   * La modificación **debe hacerse cambiando colores pixel a pixel**.
   * Puedes usar ciclos `for`, pero **no se permite indexar más de un pixel a la vez**.
   * La figura debe ser lo suficientemente grande para ser claramente visible.

4. **Comparación de histogramas**

   * Calcula y compara los histogramas de la imagen original con los de la versión modificada.
   * Muestra los resultados en gráficas y describe las diferencias.

5. **Conversión a escala de grises**

   * Convierte la imagen original a escala de grises.
   * **No se permite usar funciones predeterminadas de conversión a escala de grises** (ej. `cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)` o equivalentes).
   * Debes implementar la conversión manualmente a partir de los canales de color.

6. **Comparación con histograma en escala de grises**

   * Calcula y muestra el histograma de la imagen en escala de grises.
   * Compara este histograma con los histogramas de la imagen original.

---

## 📂 Estructura esperada del repositorio

```
├── utils.py        # Funciones implementadas
├── demo.ipynb      # Ejemplos de uso paso a paso
├── Readme.md       # Descripción clara del proceso + sección sobre IA
└── Instrucciones.md
```

---

## 📖 Contenido del archivo `Readme.md`

Tu archivo **Readme.md** debe contener:

1. Descripción del proceso realizado.
2. Ejemplos de ejecución de las funciones.
3. Resultados obtenidos (gráficas de histogramas e imágenes generadas).
4. Una sección con el siguiente formato:

---

## Nivel de uso de herramientas de inteligencia artificial

### Clasificación: \[SELECCIONA UNA OPCIÓN]

* **Sin uso de IA**: No se utilizaron herramientas de inteligencia artificial en el desarrollo de este proyecto.
* **Bajo**: Uso limitado de herramientas de IA para tareas específicas.
* **Medio**: Uso moderado de herramientas de IA para asistencia en el desarrollo.
* **Alto**: Uso extensivo de herramientas de IA para la generación y optimización del código.

### Herramientas utilizadas (si aplica)

\[Si seleccionaste "Bajo", "Medio" o "Alto", describe las herramientas específicas utilizadas]

#### Ejemplos de prompts utilizados:

\[Incluye ejemplos específicos de los prompts que utilizaste con cada herramienta]

**Ejemplo para generación de código:**

```
Prompt: "Crea un archivo Python que demuestre el uso de numpy, pandas y matplotlib para análisis de datos básicos"
```

---

## ✅ Recomendaciones

* Usa nombres de funciones claros y documenta cada función en `utils.py`.
* En `demo.ipynb` asegúrate de mostrar ejemplos de uso de **todas las funciones** implementadas.
* Los gráficos de histogramas deben estar bien rotulados (ejes, títulos, colores).
* Las imágenes resultantes deben guardarse localmente para ser visualizadas en el notebook, pero no es necesario incluirlas en el repositorio (pueden añadirse al `.gitignore`).
