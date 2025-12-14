# Tablero de Power BI - NBA Data (2012-2024)

Tablero interactivo de Power BI que visualiza datos de la NBA desde la temporada 2012 hasta 2024, proporcionando análisis detallados de estadísticas de equipos y partidos.

## 📊 Descripción del Proyecto

Este proyecto contiene un tablero de Power BI desarrollado para analizar datos de partidos de la NBA durante las temporadas 2012-2024. El tablero incluye visualizaciones y medidas personalizadas que permiten explorar estadísticas de equipos, rendimiento en partidos, y tendencias a lo largo del tiempo.

## 📁 Estructura del Proyecto

```
Power-BI/
│
├── Tablero_Medidas_Power_Bi.pbix      # Archivo principal del tablero de Power BI
├── final_data.csv                      # Dataset procesado con datos de partidos de la NBA
├── NBA Data (2012-2024).zip           # Dataset original comprimido
├── Referecia_DataSet.txt              # Referencia a la fuente del dataset
├── fondo-marco-alambre...avif         # Imagen de fondo para el tablero
└── README.md                           # Este archivo
```

## 📈 Dataset

### Fuente de Datos

El dataset proviene de Kaggle:
- **URL**: https://www.kaggle.com/datasets/kevinpickelman/nba-data-2012-2024
- **Autor**: Kevin Pickelman
- **Período**: Temporadas 2012-2024 (NBA Regular Season)

### Estructura de Datos

El archivo `final_data.csv` contiene las siguientes columnas principales:

#### Identificadores
- `GAME_ID`: Identificador único del partido
- `TEAM_ID`: Identificador único del equipo
- `TEAM_NAME`: Nombre completo del equipo
- `TEAM_ABBREVIATION`: Abreviación del equipo (ej: LAL, BOS, GSW)
- `TEAM_CITY`: Ciudad del equipo

#### Contexto del Partido
- `HOME_TEAM`: Indica si el equipo jugó como local
- `SEASON`: Temporada (formato: 12, 13, 14, etc.)
- `RESULT`: Resultado del partido (0 = Derrota, 1 = Victoria)
- `COVID_FLAG`: Bandera que indica si el partido se jugó durante la pandemia de COVID-19

#### Estadísticas de Tiro
- `FGM`: Tiros de campo convertidos
- `FGA`: Tiros de campo intentados
- `FG_PCT`: Porcentaje de tiros de campo
- `FG3M`: Tiros de 3 puntos convertidos
- `FG3A`: Tiros de 3 puntos intentados
- `FG3_PCT`: Porcentaje de tiros de 3 puntos
- `FTM`: Tiros libres convertidos
- `FTA`: Tiros libres intentados
- `FT_PCT`: Porcentaje de tiros libres
- `EFG_PCT`: Porcentaje efectivo de tiros de campo

#### Estadísticas de Rebotes
- `OREB`: Rebotes ofensivos
- `DREB`: Rebotes defensivos
- `REB`: Total de rebotes

#### Otras Estadísticas
- `MIN`: Minutos jugados
- `AST`: Asistencias
- `STL`: Robos
- `BLK`: Bloqueos
- `TO`: Pérdidas de balón
- `PF`: Faltas personales
- `PTS`: Puntos totales
- `PLUS_MINUS`: Diferencial de puntos (+/-)
- `PIE`: Player Impact Estimate (índice de impacto del jugador)
- `WIN_PCT`: Porcentaje de victorias del equipo

## 🚀 Uso del Tablero

### Requisitos Previos

- **Power BI Desktop**: Descarga gratuita desde [Microsoft Power BI](https://powerbi.microsoft.com/desktop/)
- **Power BI Service** (opcional): Para publicar y compartir el tablero online

### Instrucciones de Apertura

1. Abre Power BI Desktop en tu computadora
2. Abre el archivo `Tablero_Medidas_Power_Bi.pbix`
3. Si los datos no se cargan automáticamente:
   - Ve a "Inicio" → "Editar consultas"
   - Asegúrate de que la ruta al archivo `final_data.csv` sea correcta
   - Actualiza las consultas si es necesario

### Características del Tablero

El tablero incluye:
- **Visualizaciones interactivas** de estadísticas de equipos
- **Medidas personalizadas** en DAX para análisis avanzado
- **Filtros dinámicos** por temporada, equipo, y período
- **Gráficos de tendencias** temporales
- **Comparativas** entre equipos y temporadas

## 📊 Análisis Disponibles

El tablero permite analizar:

1. **Rendimiento de Equipos**: Estadísticas de tiro, rebotes, asistencias y puntos
2. **Tendencias Temporales**: Evolución de equipos a lo largo de las temporadas
3. **Comparativas**: Comparación entre equipos y temporadas
4. **Impacto de COVID-19**: Análisis de cómo afectó la pandemia al rendimiento
5. **Estadísticas de Local/Visitante**: Rendimiento en casa vs. fuera
6. **Métricas Avanzadas**: PIE (Player Impact Estimate), EFG% y otras métricas avanzadas

## 🔧 Mantenimiento

### Actualización de Datos

Para actualizar el tablero con nuevos datos:

1. Reemplaza el archivo `final_data.csv` con la versión actualizada
2. En Power BI Desktop, ve a "Inicio" → "Actualizar"
3. Guarda el archivo `.pbix`

### Modificación de Medidas

Las medidas personalizadas están definidas en el tablero usando DAX (Data Analysis Expressions). Para modificarlas:

1. Abre el panel de campos
2. Busca las medidas personalizadas
3. Haz clic derecho → "Editar medida"

## 📝 Notas

- El dataset original puede encontrarse en el archivo ZIP incluido o descargarse desde Kaggle
- El archivo `final_data.csv` es una versión procesada del dataset original
- La imagen de fondo (`fondo-marco-alambre...avif`) se utiliza para el diseño visual del tablero

## 🤝 Contribuciones

Este es un proyecto de análisis de datos de la NBA. Las contribuciones para mejorar las visualizaciones o añadir nuevas métricas son bienvenidas.

## 📄 Licencia

Los datos provienen de Kaggle bajo la licencia correspondiente del autor original. El tablero de Power BI es de uso libre para fines educativos y de análisis.

## 🔗 Referencias

- [Dataset Original en Kaggle](https://www.kaggle.com/datasets/kevinpickelman/nba-data-2012-2024)
- [Documentación de Power BI](https://docs.microsoft.com/power-bi/)
- [Guía de DAX](https://docs.microsoft.com/dax/)

---

**Desarrollado para análisis de datos deportivos de la NBA (2012-2024)**

