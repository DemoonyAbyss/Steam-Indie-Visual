#  Estilos Visuales en Videojuegos Indie de Steam

**Proyecto Integrador — Servicios Multimedia en la Nube**  
Ingeniería en Diseño Multimedia · UNACAR · 2026  
**Alumna:** Dominique Alessandra Ugarte González

---

## Pregunta de investigación

> ¿Qué estilos visuales (pixel art, low poly, hand-drawn, minimalista, etc.) predominan entre los videojuegos indie más exitosos de Steam, y existe alguna correlación entre dichos estilos y métricas de popularidad como valoraciones positivas y número estimado de propietarios?

## Descripción

Proyecto de Ciencia de Datos que analiza el catálogo indie de Steam para identificar patrones entre el estilo visual de los juegos y su desempeño en la plataforma. Se utilizó la SteamSpy API como fuente de datos, Python/pandas para el procesamiento, y matplotlib/seaborn para las visualizaciones.

## Estructura del repositorio

```
steam-indie-visual/
│
├── index.html                  ← Página web con resultados (GitHub Pages)
│
├── assets/                     ← Gráficas generadas
│   ├── fig1_distribucion_estilos.png
│   ├── fig2_valoracion_estilo.png
│   ├── fig3_owners_boxplot.png
│   ├── fig4_evolucion_temporal.png
│   ├── fig5_heatmap_correlacion.png
│   ├── fig6_scatter_val_owners.png
│   └── fig7_precio_exito.png
│
├── data/
│   └── steam_indie_dataset.csv ← Dataset limpio (1,500 registros)
│
├── notebook/
│   └── steam_indie_analysis.ipynb ← Libreta de análisis (abrir en Colab)
│
└── README.md
```

## Tecnologías utilizadas

| Herramienta | Uso |
|-------------|-----|
| Python 3.12 | Lenguaje principal |
| Google Colab | Entorno de ejecución en la nube |
| pandas | Manipulación y limpieza de datos |
| matplotlib / seaborn | Visualizaciones |
| SteamSpy API | Fuente de datos |
| GitHub Pages | Publicación de resultados |


## Hallazgos principales

- **Pixel Art** es el estilo más frecuente (~32%), pero no el mejor valorado
- **Hand-Drawn** obtiene la valoración positiva más alta (81.4%)
- La correlación entre estilo visual y popularidad comercial es débil (r ≈ 0.009)
- El precio no determina el éxito de un juego indie

## Página web

🌐 [Ver resultados en GitHub Pages](https://demoonyabyss.github.io/Steam-Indie-Visual/)

---

*Materia: Servicios Multimedia en la Nube · Modalidad: Ciencia de Datos*
