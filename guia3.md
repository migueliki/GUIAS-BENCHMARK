# 3. Cinebench

## 📌 Introducción
**Cinebench** es el benchmark estándar para evaluar rendimiento de hardware:
- Utiliza el motor de renderizado **Cinema 4D** (usado en producción profesional)
- Evalúa:
  - **CPU**: Rendimiento en renderizado 3D
  - **GPU**: Capacidad gráfica con OpenGL
- Permite comparar resultados con otros sistemas a nivel mundial

## 📥 Descarga e Instalación
### Descargar:
- Versión más reciente desde [Maxon.net](https://www.maxon.net/en/cinebench)

### Instalar:
1. Descargar el archivo ZIP portable
2. Extraer en cualquier carpeta
3. Ejecutar directamente `Cinebench.exe` (no requiere instalación)

![Página de descarga de Cinebench](https://www.maxon.net/wp-content/uploads/2022/03/cinebench-download-page.png)

## 🛠 Uso Básico
### Ejecución de pruebas:
1. **Prueba de CPU**:
   - Haz clic en "Run" (▶️)
   - Se ejecutará:
     - Prueba Single Core (1 núcleo)
     - Prueba Multi Core (todos los núcleos)
   - Duración aproximada: 2-10 minutos según CPU

2. **Prueba de GPU**:
   - Haz clic en "Run GPU" (▶️)
   - Mide FPS en escena 3D interactiva
   - Duración: ~1 minuto

### Interpretación de resultados:
- **Puntuación CPU**:
  - Valores más altos = mejor rendimiento
  - Comparativa referencia (R23):
    | Procesador       | Multi Core | Single Core |
    |------------------|------------|-------------|
    | Ryzen 9 7950X    | ~38,000    | ~2,000      |
    | i9-13900K        | ~35,000    | ~2,200      |

- **Puntuación GPU**:
  - Se mide en FPS (Cuadros por segundo)
  - Valores típicos:
    - GPU integrada: 20-50 FPS
    - GPU media gama: 80-120 FPS
    - GPU alta gama: 200+ FPS

![Resultados típicos en Cinebench](https://www.overclockers.ua/news/software/123970-cinebench-r20-1s.jpg)

> 💡 **Consejos profesionales**:
> - Cierra todas las aplicaciones antes de ejecutar
> - Ejecuta como administrador para máxima prioridad
> - Para comparativas, usa siempre la misma versión de Cinebench
> - Los resultados pueden variar ±5% entre ejecuciones

> 🌡 **Nota sobre temperaturas**:
> Durante el test Multi Core, es normal que:
> - CPUs de alto rendimiento alcancen 80-90°C
> - Consumo de energía llegue al máximo TDP