## **Sistema Experto Difuso para la Optimización del Consumo de Energía en el Hogar**

### **Introducción**
Este proyecto propone un sistema experto desarrollado en CLIPS para optimizar el uso de energía en un entorno doméstico. Utiliza reglas lógicas y un enfoque basado en hechos para diagnosticar problemas de consumo energético, priorizar dispositivos y sugerir cambios para mejorar la eficiencia y reducir los costos.

---

### **Funciones Principales**
- **Análisis de Consumo:** Identifica dispositivos con alto consumo energético.
- **Gestión por Prioridades:** Asigna prioridades a los dispositivos según su relevancia y horario de uso.
- **Optimización Horaria:** Recomienda el uso de dispositivos en horarios de bajo costo energético.
- **Diagnóstico Automatizado:** Ofrece sugerencias para minimizar el consumo durante los horarios pico.

---

### **Contenido del Proyecto**
- **`reglas.clp`:** Código principal que contiene las plantillas, hechos y reglas del sistema experto.
- **`README.md`:** Documentación detallada del proyecto.

---

### **Requisitos**
- **CLIPS:** Descárgalo desde el sitio oficial [clipsrules.net](https://www.clipsrules.net/) y configúralo en tu sistema.

---

### **Guía de Uso**
1. **Abrir CLIPS:** Inicia el entorno desde tu sistema.
2. **Cargar el archivo del sistema:**
   ```clips
   (load "ruta/completa/al/archivo/reglas.clp")
   ```
3. **Inicializar el sistema:**
   ```clips
   (reset)
   ```
4. **Ejecutar las reglas:**
   ```clips
   (run)
   ```
5. **Revisar los resultados:** Las recomendaciones y diagnósticos aparecerán en la consola.

---

### **Ejemplo de Diagnóstico**
#### Entrada:
Dispositivo: Lavadora
- Consumo: 500W
- Horario: Día
- Costo de Energía: Alto

#### Resultado:
- "El dispositivo Lavadora tiene un consumo elevado. Se recomienda reducir su uso en horarios pico para optimizar los costos."

---

### **Posibles Mejoras Futuras**
- Integración con dispositivos inteligentes para monitoreo en tiempo real.
- Inclusión de predicciones de consumo basadas en aprendizaje automático.
- Ampliación de las reglas para cubrir más dispositivos y escenarios.

---

### **Licencia**
Este proyecto puede incluirse bajo una licencia abierta como MIT, Apache 2.0, o cualquier otra que consideres adecuada.

