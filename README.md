# Simulador-OLS
📘 Simulación OLS en Gretl: Estimadores, Estadística Descriptiva e Intervalos
Este script en Gretl permite simular 1,000 regresiones OLS generadas artificialmente, con salida tabular clara y estadísticas relevantes al final. Está pensado como herramienta educativa y exploratoria sobre el comportamiento de los estimadores bajo condiciones ideales.
🔧 ¿Qué hace este script?
- Simula 1,000 muestras de datos aleatorios con dos regresores explicativos (x1, x2) y un término de error normal.
- Ejecuta una regresión OLS para cada muestra usando:
- [ y = 2 + 1.5x_1 - 0.5x_2 + u ]
- Guarda los betas estimados (β₀, β₁, β₂) de cada simulación.
- Calcula:
- Media y desviación estándar de cada coeficiente.
- Intervalos de confianza al 95% (percentiles 2.5% y 97.5%).
- Exporta todos los resultados a un archivo .csv con etiquetas amigables.
- Imprime:
- Las primeras 10 simulaciones.
- El resumen estadístico.
- Intervalos de confianza.
- Una tabla final con las últimas 10 simulaciones + media y desviación estándar.
📂 Archivos generados
- betas_1000_con_etiquetas.csv → Matriz completa con betas + filas de media y desviación estándar.
✅ Requisitos
- Gretl versión 2025b o posterior.
- No requiere paquetes adicionales.
💡 Notas adicionales
- Este script puede modificarse fácilmente para incluir multicolinealidad, heterocedasticidad u otras distorsiones del modelo clásico de regresión lineal.
- Se puede usar como plantilla para cursos de econometría, pruebas de robustez o como comparación frente a estimadores robustos.
