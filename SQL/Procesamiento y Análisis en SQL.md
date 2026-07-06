## 🗄️ Procesamiento y Modelado en SQL

Como parte del desarrollo del proyecto **RetailX Analytics**, se utilizó SQL para la preparación, transformación y estructuración de los datos, alineado con el modelo dimensional definido en el dashboard.

### 🔧 Extracción y Limpieza de Datos
- Consulta de datos desde las tablas fuente de ventas  
- Validación de registros nulos y duplicados  
- Estandarización de formatos (fechas, categorías, identificadores)  
- Filtrado de datos inconsistentes o incompletos  

---

### 🔄 Transformación de Datos
- Creación de métricas base:
  - Total de ventas (`Total Amount`)  
  - Cantidad de productos (`Quantity`)  
  - Precio por unidad (`Price per Unit`)  
- Generación de columnas derivadas:
  - Año, mes y periodo para análisis temporal  
  - Segmentos de clientes (edad, género)  
  - Agregaciones para análisis:
  - Ventas por categoría  
  - Ventas por segmento  
  - Ventas mensuales  

---

### 🧩 Construcción del Modelo Dimensional
Se estructuró la información bajo un esquema tipo **estrella (Star Schema)**:

- **Tabla de hechos (Fact Table):**
  - Contiene métricas de negocio (ventas, cantidades, ingresos)

- **Tablas de dimensiones:**
  - Dimensión Cliente  
  - Dimensión Producto  
  - Dimensión Tiempo  
  - Dimensión Categoría  

- Definición de claves primarias y foráneas para asegurar integridad referencial  

---

### 📊 Preparación para BI
- Creación de vistas o tablas finales optimizadas para consumo en Power BI  
- Validación de consistencia entre métricas SQL y análisis en Python  
- Optimización de consultas para mejorar rendimiento del dashboard  

---

### ✅ Resultado
El uso de SQL permitió:
- Consolidar y estructurar los datos de manera eficiente  
- Garantizar la calidad e integridad de la información  
- Proveer una base sólida para el análisis en Python y la visualización en Power BI  

