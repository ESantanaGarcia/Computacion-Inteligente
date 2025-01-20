Sistema Experto Difuso para la Optimización del Consumo de Energía en el Hogar

Introducción

Este proyecto propone un sistema experto desarrollado en CLIPS para optimizar el uso de energía en un entorno doméstico. Utiliza reglas lógicas y un enfoque basado en hechos para diagnosticar problemas de consumo energético, priorizar dispositivos y sugerir cambios para mejorar la eficiencia y reducir los costos.

Funciones Principales

Análisis de Consumo: Identifica dispositivos con alto consumo energético.

Gestión por Prioridades: Asigna prioridades a los dispositivos según su relevancia y horario de uso.

Optimización Horaria: Recomienda el uso de dispositivos en horarios de bajo costo energético.

Diagnóstico Automatizado: Ofrece sugerencias para minimizar el consumo durante los horarios pico.

Contenido del Proyecto

reglas.clp: Código principal que contiene las plantillas, hechos y reglas del sistema experto.

README.md: Documentación detallada del proyecto.

Requisitos

CLIPS: Descárgalo desde el sitio oficial clipsrules.net y configúralo en tu sistema.

Guía de Uso

Abrir CLIPS: Inicia el entorno desde tu sistema.

Cargar el archivo del sistema:

(load "ruta/completa/al/archivo/reglas.clp")

Inicializar el sistema:

(reset)

Ejecutar las reglas:

(run)

Revisar los resultados: Las recomendaciones y diagnósticos aparecerán en la consola.

Ejemplo de Diagnóstico

Entrada:

Dispositivo: Lavadora

Consumo: 500W

Horario: Día

Costo de Energía: Alto

Resultado:

"El dispositivo Lavadora tiene un consumo elevado. Se recomienda reducir su uso en horarios pico para optimizar los costos."

