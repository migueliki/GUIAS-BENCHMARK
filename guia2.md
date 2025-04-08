# 2. OCCT

## 📌 Introducción
**OCCT** es un programa de estrés y monitoreo para componentes de PC:
- Evalúa estabilidad de CPU, GPU y RAM bajo carga extrema
- Detecta problemas como:
  - Overheating (sobrecalentamiento)
  - Errores de voltaje
  - Inestabilidad del sistema
- Ideal para testear overclocks y refrigeración

## 📥 Descarga e Instalación
### Descargar:
- Versión gratuita desde [OCBASE.com](https://www.ocbase.com/)

### Instalar:
1. Ejecutar el instalador descargado
2. Seleccionar componentes adicionales (recomendado HWMonitor para sensores)
3. Completar la instalación guiada

![Pantalla de descarga OCCT](https://www.ocbase.com/images/occt-download-page.png)

## 🛠 Uso Básico
### Configurar prueba de estrés:
1. **Seleccionar componente a testear**:
   - CPU (OCCT o Linpack)
   - GPU (3D Standard o VRAM)
   - Fuente de alimentación (Power Supply)

2. **Ajustar parámetros**:
   - Duración (mínimo 10-15 minutos para resultados válidos)
   - Nivel de carga (Small/Medium/Large Data Set)
   - Monitorización activada

3. **Iniciar prueba**:
   - Click en "Start" para comenzar
   - Monitorizar valores en tiempo real

### Interpretar resultados:
- **Gráficos en tiempo real** muestra:
  - Temperaturas (CPU/GPU)
  - Voltajes (12V, 5V, 3.3V)
  - Consumo energético
  - Frecuencias de reloj

- **Errores detectados**:
  - Mensaje "Errors detected" = sistema inestable
  - Warnings por temperaturas altas (>90°C CPU / >95°C GPU)

![Interfaz de OCCT en funcionamiento](https://www.ocbase.com/images/occt-main-screen.png)

> ⚠️ **Advertencia importante**: 
> - No ejecutar pruebas prolongadas en laptops sin refrigeración adecuada
> - Monitorear temperaturas constantemente
> - Detener prueba inmediatamente si se superan 95°C en CPU

> 💡 **Tip profesional**: Usa el modo "Auto" para que OCCT detenga la prueba automáticamente al detectar errores o temperaturas peligrosas.