Análisis de Comportamiento de Clientes — ConnectaTel

Descripción del proyecto

Análisis exploratorio de datos para ConnectaTel, empresa de telecomunicaciones
con operaciones en México y Colombia. El objetivo es entender cómo los clientes
usan los servicios móviles (llamadas y mensajes), detectar comportamientos
atípicos y construir segmentos accionables que orienten decisiones comerciales.

Datasets utilizados

| Archivo | Descripción |
|---|---|
| `plans.csv` | Catálogo de planes: precio, minutos incluidos, GB, costo por extra |
| `users_latam.csv` | Información de clientes: edad, ciudad, fecha de registro, plan, churn |
| `usage.csv` | Actividad real: llamadas, mensajes, duración y longitud |


Etapas del análisis

1. **Carga y exploración** — revisión de estructura, tipos de datos y primeras filas.
2. **Identificación de problemas de calidad** — nulos, sentinels y fechas fuera de rango.
3. **Limpieza de datos** — reemplazo de sentinels, conversión de fechas, decisiones MAR.
4. **Resumen estadístico** — métricas de uso agregadas por usuario y distribución de planes.
5. **Visualización y outliers** — histogramas y boxplots por columna y por plan.
6. **Segmentación** — clasificación por nivel de uso (Bajo / Medio / Alto) y por edad (Joven / Adulto / Adulto Mayor).
7. **Insight ejecutivo** — conclusiones y recomendaciones comerciales para stakeholders.

8. ## 📌 Guía de reproducción

1. Clona el repositorio o descarga los archivos.
2. Asegúrate de tener los tres datasets en la misma carpeta que el notebook,
   o actualiza las rutas de `pd.read_csv()` según tu entorno.
3. Ejecuta las celdas en orden secuencial; cada paso depende del anterior.
4. Las celdas de texto con `✍️` contienen el diagnóstico del analista
   y no requieren ejecución.

---

## 👤 Autor

**[Longoria Salazar Jorge Esau]**  
Analista de Datos Jr.
