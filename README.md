# 🎮 Patrones de éxito y fracaso en la industria de los videojuegos 
Análisis de datos de videojuegos para identificar patrones asociados al éxito o fracaso en sus ventas.

## 📄 Descripción del proyecto
Trabajamos en "Ice", una tienda online especializada en la venta de videojuegos en todo el mundo. Nuestro análisis se basa en diversas fuentes de datos, incluidas reseñas de usuarios y expertos, géneros de juegos, plataformas (como Xbox o PlayStation) y datos históricos de ventas, todos ellos disponibles públicamente.

Nuestro objetivo es descubrir patrones que definan el éxito o la falta de éxito de un juego. De este modo, podemos identificar los juegos con mayor potencial y desarrollar campañas publicitarias eficaces. Nuestro conjunto de datos cubre el año 2016 y utilizaremos esta información para diseñar estrategias para nuestras campañas para 2017.

## 🎯 Objetivos del proyecto
Los objetivos de este proyecto son los siguientes:

1. Realizar un análisis para identificar patrones que contribuyan al éxito o fracaso de un juego.
2. Brindar recomendaciones de juegos que muestren potencial de publicidad para mejorar las ventas en 2017.
3. Probar dos hipótesis:
- Determinar si las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son iguales.
- Determinar si las calificaciones promedio de los usuarios para los géneros Acción y Deportes son diferentes.

## 🛠 Etapas de finalización del proyecto
Analizaremos los datos almacenados en el archivo `games.csv`. Aunque tenemos cierta información preliminar sobre los datos, necesitamos evaluar su calidad.

Nuestro análisis implicará varias etapas:

1. 📊 Descripción inicial de los datos: Proporcionaremos una breve descripción general de los datos, incluida la información general y las estadísticas clave.
2. 🔧 Preprocesamiento de los datos: Mejoraremos la calidad de los datos realizando tareas como leer y validar los datos, cambiar el nombre de las columnas, manejar los valores faltantes, ajustar los tipos de datos y crear nuevas columnas relevantes.
3. 🔍 Análisis exploratorio de datos: Exploraremos los datos para descubrir patrones y conocimientos relacionados con el rendimiento de las ventas de videojuegos. Presentaremos nuestros hallazgos, conocimientos y recomendaciones.
4. 📈 Análisis estadístico de los datos: Realizaremos pruebas estadísticas para examinar dos hipótesis aceptadas.
5. 📝Conclusión: Resumiremos los resultados de nuestro análisis y proporcionaremos conclusiones generales.

A lo largo de estas etapas, nos aseguraremos de realizar un análisis integral de los datos para obtener información valiosa sobre las ventas de videojuegos.

## 📊 Descripción de los datos
A continuación se incluye una descripción de los datos utilizados para nuestro análisis:

- `Name`: el nombre del juego.
- `Platform`: la(s) plataforma(s) en las que está disponible el juego.
- `Year_of_Release`: el año en que se lanzó el juego.
- `Genre`: el género o la categoría del juego.
- `NA_sales`: ventas del juego en Norteamérica, medidas en millones de USD.
- `EU_sales`: ventas del juego en Europa, medidas en millones de USD.
- `JP_sales`: ventas del juego en Japón, medidas en millones de USD.
- `Other_sales`: ventas del juego en otros países, medidas en millones de USD.
- `Critic_Score`: la puntuación de las reseñas otorgadas por los críticos, con una puntuación máxima de 100.
- `User_Score`: la puntuación de las reseñas otorgadas por los usuarios, con una puntuación máxima de 10.
- `Rating`: la calificación asignada por la Entertainment Software Rating Board (ESRB).

Estas variables proporcionan información importante sobre los juegos, incluido su desempeño en ventas, reseñas críticas y de usuarios, y calificaciones de la ESRB.

A continuación, se muestra el significado de cada clasificación según el sitio web de la ESRB:

- **E** (Everyone): contenido apto para todas las edades.
- **T** (Teen): contenido apto para adolescentes de 13 años o más.
- **M** (Mature): contenido apto para adultos de 17 años o más.
- **E10+** (Everyone 10 and older): contenido apto para todos los mayores de 10 años.
- **K-A** (Kids to adults): contenido apto para todas las edades. Esta era la clasificación utilizada antes de que se cambiara a E en 1999.
- **AO** (Adults only): contenido apto solo para adultos de 18 años o más.
- **EC** (Early Childhood): contenido apto para niños de 3 años o más.
- **RP** (Rating Pending): la ESRB aún no ha emitido clasificaciones.

## 📚 Librerías 
- Pandas
- NumPy
- matplotlib
- seaborn
- Scipy

## ⚖️ Licencia
Este proyecto está bajo la licencia Creative Commons Attribution-NonCommercial 4.0 International Public License (CC BY-NC 4.0). Eres libre de usar, compartir y adaptar este trabajo para fines no comerciales, siempre que se dé el crédito adecuado. Para más detalles, consulta el archivo [LICENCIA](./LICENSE) o visita [Creative Commons](https://creativecommons.org/licenses/by-nc/4.0/).
