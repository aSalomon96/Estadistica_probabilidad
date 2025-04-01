# Prueba A/B Testing para Optimización de Conversiones 📊

## Descripción del Proyecto 📝
Este proyecto tiene como objetivo analizar una prueba A/B para evaluar el impacto de diferentes versiones de una página web en la conversión de usuarios. Se busca determinar si existe una diferencia estadísticamente significativa entre los grupos de prueba (A y B) en términos de tasa de conversión.

El análisis incluye:

- **Cálculo de tasas de conversión**: Determinar qué grupo tiene una mejor performance en términos de conversión.
- **Análisis por dispositivo y ubicación**: Evaluar si existen diferencias en la conversión según el tipo de dispositivo (Mobile/Desktop) y la ubicación geográfica.
- **Visualización de datos**: Uso de gráficos para representar las tasas de conversión y diferencias entre grupos.
- **Pruebas estadísticas**: Aplicación de pruebas de hipótesis para validar si las diferencias observadas son significativas.

## Estructura del Proyecto 🗂️
```
├── data/                               
│   ├── ab_testing.csv                   # Datos de la prueba A/B
├──notebook/
│   ├── Proyecto.ipynb                   # Archivo de proyecto
├── src/                                 
│   ├── soporte_abtesting.py             # Funciones auxiliares
├── README.md                            # Descripción del proyecto
```

## Instalación y Requisitos 🛠️
Este proyecto utiliza **Python 3.9** 🐍 y requiere las siguientes librerías:

```bash
pip install pandas matplotlib seaborn scipy math statsmodels
```

## Limpieza de Datos 🧹
Para garantizar un análisis preciso, se realizaron los siguientes pasos:

- **Conversión de datos**: Se transformó la variable `Conversion` de formato "Yes/No" a valores binarios (1 = Yes, 0 = No).
- **Eliminación de valores nulos**: Se verificó la integridad de los datos y se eliminaron registros incompletos.
- **Conversión de tipos**: Se aseguraron los formatos correctos para cada variable (numérico, categórico, etc.).

## Resultados y Análisis 📊

### 1. Comparación de tasas de conversión por grupo
- Se calculó la tasa de conversión para los grupos A y B.
- Se observó que existen diferencias en la conversión entre los grupos.

### 2. Análisis por dispositivo y ubicación
- **Desktop** tiene una mayor tasa de conversión en comparación con **Mobile**.
- **Inglaterra** presenta la mayor cantidad de conversiones, mientras que **Irlanda del Norte** tiene las menores.
- Las diferencias en conversión entre dispositivos son más marcadas en **Desktop** que en **Mobile**.

### 3. Pruebas estadísticas
- Se realizó una **prueba de hipótesis (test de proporciones)** para determinar si las diferencias observadas son estadísticamente significativas.
- Los resultados indicaron que la diferencia entre los grupos **es significativa**, lo que sugiere que la versión de la página asignada al grupo con mejor conversión tiene un impacto real en los usuarios.

## Conclusiones 📌
El análisis demuestra que existen diferencias en la tasa de conversión entre los grupos A y B, siendo un resultado clave para la optimización de estrategias digitales. Además:

- **Los usuarios de Desktop convierten más que los de Mobile**, lo que sugiere que la experiencia en móviles podría necesitar mejoras.
- **Inglaterra es el mercado con mejor conversión**, por lo que se podrían enfocar estrategias de marketing específicas para esa región.
- **Las diferencias son significativas** y justifican la adopción de la versión con mejor rendimiento.

## Próximos Pasos 🔄
- Profundizar en el análisis segmentando aún más por variables como tiempo de permanencia en la página.
- Evaluar el impacto de cambios adicionales en la página para mejorar la experiencia móvil.
- Aplicar modelos de predicción para anticipar el comportamiento de conversión en diferentes grupos.

## Contribuciones 🤝
¡Las contribuciones son bienvenidas! Si deseas colaborar, abre un pull request o crea una issue para discutir tus ideas. Se valoran especialmente las contribuciones en análisis estadístico y visualización de datos.

## Autores y Agradecimientos ✒️
📌 **Autor**: Agustín Salomón
📌 **GitHub**: [aSalomon96](https://github.com/aSalomon96)
📌 **LinkedIn**: [Agustín Salomón](https://www.linkedin.com/in/agustin-salomon/)

