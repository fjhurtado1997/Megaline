# Megaline

# 📱 Análisis de Planes Telefónicos - Megaline

Análisis estadístico completo de los planes telefónicos de la empresa Megaline para determinar cuál genera más ingresos.

## 🎯 Objetivo del Proyecto

Analizar el comportamiento de los clientes de Megaline y determinar qué plan telefónico (Surf o Ultimate) es más rentable para la empresa.

## 📊 Descripción de los Datos

El proyecto utiliza datos de 500 usuarios de Megaline del año 2018, incluyendo:

- **Información de usuarios**: plan, fecha de registro, ciudad
- **Datos de llamadas**: duración, fecha, costo
- **Datos de mensajes**: cantidad, fecha, costo  
- **Datos de internet**: tráfico consumido, fecha, costo
- **Información de planes**: límites mensuales y tarifas

## 🔍 Análisis Realizado

### 1. **Análisis Exploratorio**
- Comportamiento de usuarios por plan
- Patrones de consumo mensual
- Distribución geográfica de usuarios

### 2. **Análisis Estadístico**
- Cálculo de ingresos por usuario
- Análisis de consumo promedio
- Identificación de usuarios que exceden límites

### 3. **Pruebas de Hipótesis**
- **H₀**: Los ingresos promedio de ambos planes son iguales
- **H₁**: Los ingresos promedio difieren entre planes
- Comparación entre regiones (NY vs otras)

## 📈 Principales Hallazgos

- Plan **Ultimate** genera mayor ingreso promedio por usuario
- Usuarios de **Surf** frecuentemente exceden límites
- Diferencias significativas entre regiones
- Recomendaciones para optimización de planes

## 🛠️ Tecnologías Utilizadas

- **Python 3.8+**
- **Pandas** - Manipulación de datos
- **NumPy** - Cálculos numéricos
- **Matplotlib** - Visualizaciones básicas
- **Seaborn** - Visualizaciones avanzadas
- **SciPy** - Pruebas estadísticas
