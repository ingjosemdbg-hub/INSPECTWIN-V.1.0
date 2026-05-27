# INSPECTWIN — Visor 3D de Activos Fotogramétricos

Visor web standalone para inspección visual de modelos fotogramétricos 3D de infraestructura (puentes, taludes, edificios).

## 🚀 Acceso rápido

**[▶ Abrir INSPECTWIN](https://TU-USUARIO.github.io/inspectwin)**

## 📋 Características

- Carga de modelos **3D Tiles** (`.3tz`, `.zip`, `tileset.json`, `.glb`)
- Múltiples modelos simultáneos con control de visibilidad
- **Herramientas de medición**: distancia, área, punto UTM, ángulo de inclinación, perfil topográfico
- **Anotaciones georreferenciadas**: puntos, líneas y polígonos con tipo de deterioro, severidad y componente estructural
- **Exportación**: GeoJSON, CSV, JSON con datos del puente
- **Importación**: GeoJSON y JSON de INSPECTWIN
- **Reporte PDF** con datos generales del puente y estadísticas de deterioro
- Plano de corte X/Y/Z con control fino
- Mapa base satélital (Google/ESRI)
- Panel de resumen estadístico por componente
- Modo claro/oscuro

## 📁 Formatos de modelo soportados

| Formato | Descripción |
|---------|-------------|
| `.3tz` | Metashape 2.2+ (recomendado) |
| `.zip` | Metashape 2.0–2.1 |
| `tileset.json` | 3D Tiles con servidor local |
| `.glb` / `.gltf` | Modelos simples |

## 🗂️ Tipos de deterioro

Fisura, Grieta, Desconchadura, Acero expuesto, Corrosión, Carbonatación, Humedad, Eflorescencias, Socavación, Bache, Pintura, Erosión, Asolve, Vegetación, Anclajes, Impactos, Vandalismo

## 📐 Componentes estructurales

- Superficie de rodadura
- Superestructura
- Subestructura
- Cimentación
- Obras de drenaje

## 🛠️ Tecnologías

- [CesiumJS 1.114](https://cesium.com) — motor 3D
- [JSZip](https://stuk.github.io/jszip/) — descompresión de .3tz
- HTML/CSS/JavaScript puro — sin frameworks, sin instalación

## 📄 Uso

1. Abre el visor desde el enlace de GitHub Pages
2. Arrastra o selecciona tu archivo `.3tz` en el panel izquierdo
3. Usa las herramientas de la barra superior para medir y anotar
4. Exporta tus anotaciones en GeoJSON o JSON
5. Genera el reporte PDF con los datos del puente

---
Desarrollado para inspección de infraestructura vial — Michoacán, México
