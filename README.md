# Análisis de Desempeño – Alura Store

##  Propósito del análisis
El objetivo de este proyecto es analizar el desempeño de las cuatro tiendas de la cadena **Alura Store** para ayudar al Sr. Juan a tomar una decisión estratégica: identificar qué tienda debería vender para iniciar un nuevo emprendimiento.

El análisis se basa en datos de ventas reales y busca evaluar la eficiencia de cada tienda a partir de indicadores clave como:
- Ingresos totales
- Ventas por categoría
- Satisfacción del cliente
- Productos más y menos vendidos
- Costo de envío promedio (asumido por el cliente)

A partir de estos datos, se generan visualizaciones que facilitan la interpretación de patrones y permiten formular una recomendación final basada en evidencia.


## 📈 Análisis realizados

Durante el desarrollo del proyecto se llevaron a cabo los siguientes análisis:

1. **Análisis de facturación**  
   Se calcularon los ingresos totales de cada tienda sumando la columna *Precio*.

2. **Ventas por categoría**  
   Se agruparon las ventas por categoría de producto para identificar las más populares.

3. **Calificación promedio de la tienda**  
   Se calculó el promedio de las calificaciones de los clientes para medir la satisfacción.

4. **Productos más y menos vendidos**  
   Se identificaron los productos con mayor y menor número de ventas en cada tienda.

5. **Costo de envío promedio por tienda**  
   Se calculó el costo promedio de envío, considerando que este valor es asumido por el cliente.

---

##  Visualizaciones e insights obtenidos

Para facilitar la interpretación de los resultados, se generaron cuatro visualizaciones utilizando diferentes tipos de gráficos con la librería **Matplotlib**, cada una enfocada en un aspecto clave del análisis.
### 1. Ingresos totales por tienda (Gráfico de barras)
Este gráfico compara la facturación total de cada tienda.

**Insight:**  
La Tienda 4 presenta los menores ingresos totales, mientras que la Tienda 1 lidera en facturación. Esta visualización es clave para identificar la tienda con menor desempeño financiero.

### 2. Distribución de la calificación promedio por tienda (Gráfico de tortas)
Este gráfico representa la proporción de la calificación promedio de cada tienda respecto al total.

**Insight:**  
Las calificaciones de las cuatro tiendas son muy similares, lo que indica un nivel de satisfacción homogéneo entre los clientes. Aun así, pequeñas diferencias permiten identificar ligeras variaciones en la percepción del servicio.

### 3. Relación entre calificación promedio e ingresos (Gráfico de dispersión)
Este gráfico analiza la relación entre la satisfacción del cliente (calificación promedio) y los ingresos de cada tienda.

**Insight:**  
No existe una relación directa entre una mayor calificación y mayores ingresos. Por ejemplo, algunas tiendas con calificaciones similares presentan diferencias significativas en su facturación.
### 4. Costo de envío promedio por tienda (Gráfico de líneas)
Este gráfico muestra el costo de envío promedio de cada tienda.

**Insight:**  
Se observa una tendencia descendente en los costos de envío, siendo la Tienda 4 la que presenta el menor costo promedio. Sin embargo, este menor costo no se traduce en un mejor desempeño en ingresos.

En conjunto, estas visualizaciones permiten comprender de manera clara el comportamiento de las tiendas en términos de costos, ingresos y satisfacción del cliente, y respaldan la recomendación final basada en datos.

---

## Instrucciones para ejecutar el notebook

1. Asegúrate de tener instalado **Python 3**.
2. Instala las librerías necesarias:
   ```bash
   pip install pandas matplotlib
   
## Conclusión final

Tras analizar los ingresos, las categorías de venta, la satisfacción del cliente, los productos más vendidos y los costos de envío, se concluye que la Tienda 4 es la menos eficiente en términos de desempeño general.

Aunque presenta el menor costo de envío, esta ventaja no se traduce en mayores ingresos ni en una mejor posición competitiva frente a las demás tiendas. Por lo tanto, se recomienda vender la Tienda 4 para financiar el nuevo emprendimiento del Sr. Juan.
