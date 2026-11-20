# Astrobiology-BioData

Ejercicios introductorios de Python aplicados a problemas biológicos, desarrollados como primer portafolio de programación científica.

> **Nota importante:** todos los datos de este repositorio son **simulados** con fines de aprendizaje. No son resultados experimentales ni datos de organismos reales.

## Problema que se explora

¿Cómo pueden utilizarse herramientas computacionales para analizar datos biológicos de forma reproducible y representar procesos como la cuantificación de proteínas y la herencia mendeliana?

## Relevancia para Biología (y Astrobiología)

La biología actual depende del análisis de datos. Estos ejercicios practican habilidades básicas (organizar datos, ajustar modelos, visualizar y simular) que también se usan en bioinformática y en astrobiología, por ejemplo para analizar datos de laboratorio, modelar condiciones ambientales o comparar organismos extremófilos.

## Contenido

1. **Curva patrón tipo Bradford:** regresión lineal de absorbancia a 595 nm vs. concentración de BSA y estimación de proteína soluble en tres muestras de insectos. Herramientas: NumPy, Matplotlib.
2. **Simulador de genética mendeliana:** cruce Aa × Aa, comparando proporciones teóricas con una simulación de 1000 crías. Herramientas: random, collections.
3. **Contenido GC (opcional):** porcentaje de G + C en secuencuencias de ejemplo.

## Estructura del repositorio

- README.md
- notebooks/analisis_biologico.ipynb
- references/referencias.md

## Cómo ejecutarlo

1. Abre el notebook en Google Colab (https://colab.research.google.com/).
2. Ejecuta las celdas en orden (Entorno de ejecución → Ejecutar todo).
3. No requiere instalar nada: Colab ya incluye NumPy, Pandas y Matplotlib.

## Limitaciones

- Los datos son simulados; los valores no representan resultados reales.
- La curva patrón usa un ajuste lineal simple, sin réplicas ni análisis de incertidumbre.
- El método de Bradford estima proteína soluble recuperada bajo ciertas condiciones de extracción, no necesariamente la proteína total.
- La simulación mendeliana asume un solo gen, sin ligamiento ni selección.
- Estos ejercicios demuestran habilidades de análisis, no conclusiones biológicas ni astrobiológicas.

## Próximos pasos

- Reemplazar los datos simulados por mediciones reales de laboratorio, con réplicas y barras de error.
- Aprender R y explorar bibliotecas de bioinformática.
- Explorar procesamiento básico de imágenes de microscopía.

## Nivel del autor

Nivel básico de Python, en aprendizaje activo.

## Referencias

Bradford, M. M. (1976). A rapid and sensitive method for the quantitation of microgram quantities of protein utilizing the principle of protein-dye binding. *Analytical Biochemistry*, 72, 248–254.
