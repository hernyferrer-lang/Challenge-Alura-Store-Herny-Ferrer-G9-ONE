<em> ## Challenge Alura Store - Análisis de Ventas by Herny Ferrer </em>

Proyecto de análisis exploratorio de datos realizado sobre el dataset **Alura Store**, con el objetivo de identificar patrones de venta, métodos de pago más utilizados, desempeño por tienda y otros indicadores clave de facturación.

---

## Propósito del análisis

El análisis busca:
- Comprender la **distribución de ventas** por tienda y producto.
- Identificar los **métodos de pago más utilizados**.
- Evaluar la **calificación promedio** por tienda.
- Analizar la **evolución mensual de la facturación**.
- Detectar **insights** que ayuden a mejorar las estrategias comerciales.

---

## Ejemplos de gráficos e insights

### Facturación total por método de pago
Gráfico de barras horizontales que muestra qué medios de pago concentran mayor volumen de facturación.

**Insight:** El método de pago *Tarjeta de crédito* representa más del 60% de las ventas totales, indicando preferencia por el financiamiento en cuotas.

![Facturación por método de pago](images/facturacion_pago.png)

---

### Calificación promedio por tienda
Ranking de tiendas según la calificación promedio otorgada por los clientes.

**Insight:** Las tiendas con mejor atención tienen una correlación directa con un ticket promedio más alto.

![Calificación por tienda](images/calificacion_tienda.png)

---

### Mapa de calor de facturación
Mapa oscuro tipo heatmap que representa la facturación total por ubicación de tienda.

**Insight:** La zona centro presenta mayor densidad de ventas, siendo el principal polo comercial de la marca.

![Mapa de calor](images/mapa_calor.png)

---

## Instrucciones para ejecutar el notebook

1. **Cloná el repositorio**
   ```bash
   git clone https://github.com/tuusuario/alura-store.git
   cd alura-store
Instalá las dependencias

bash
Copy code
pip install -r requirements.txt
Ejecutá el notebook

bash
Copy code
jupyter notebook alura_store_analysis.ipynb
Explorá los gráficos e insights interactivos
