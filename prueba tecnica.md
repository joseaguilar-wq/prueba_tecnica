# Reto Técnico: Automatización de Reporte Operativo - Grupo Ortiz

## Contexto del Problema
En la gestión de infraestructura y maquinaria pesada, el control de insumos es vital. Un error en la interpretación de los datos puede significar pérdidas millonarias o fallas críticas en obra.

Se te ha proporcionado un archivo CSV (`consumo_maquinaria.csv`) que contiene los registros de carga de combustible y lectura de horómetros (horas de uso) de 3 excavadoras durante una semana.

## Tu Objetivo
Debes desarrollar un script (Python preferentemente) que automatice las siguientes tareas:
1. **Calcular el consumo de combustible:** Litros consumidos por hora trabajada entre cada registro.
2. **Generar Alertas:** Si una máquina consume más de **35 L/h**, debe marcarse como "ALERTA MECÁNICA".
3. **Resumen Ejecutivo:** Exportar un archivo final (JSON o Excel) con el promedio de eficiencia de cada máquina.

## Consideraciones Generales
* **Uso de IA:** Está permitido el uso de herramientas como ChatGPT, Claude o Copilot. Sin embargo, recuerda que tú eres el responsable de la validez de los resultados.
* **Privacidad:** No compartas datos sensibles de la empresa en prompts públicos (en este caso, los datos son simulados).
* **Pensamiento Crítico:** Si encuentras inconsistencias en los datos de origen, tu script debe ser capaz de detectarlas y manejarlas sin detenerse, pero notificando el error.

## Entregables
1. **Código fuente:** Limpio y documentado.
2. **Archivo de salida:** El reporte generado por tu script.
3. **Breve Video/Nota (README):** Un resumen de máximo 2 minutos (o un texto corto) explicando:
    - ¿Cómo manejaste las anomalías encontradas?
    - ¿Por qué decidiste resolverlo de esa manera en lugar de dejar que la IA lo hiciera por ti?