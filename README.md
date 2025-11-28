# 📊 Plantilla Dashboard V1 – Excel + Macros VBA
Versión profesional 2025 desarrollada para flujos operativos con control ANS, dashboards internos, filtros avanzados y generación de mapas georreferenciados directamente desde Excel.

Esta plantilla está lista para usar como base en proyectos corporativos, y funciona en equipos sin Python ni dependencias externas.

---

## 🚀 Características principales

### ✔️ 1. **Panel lateral interactivo (UI Profesional)**
Incluye:
- Búsqueda por pedido  
- Filtros por estado (A TIEMPO, ALERTA, ALERTA 0 DÍAS, VENCIDO, SIN FECHA)  
- Selector de actividad  
- Botón de centrar mapa  
- Limpieza rápida de filtros  

Todo con botones estilizados en un panel tipo “dashboard web”.

---

### ✔️ 2. **Generación de Mapa ANS desde Excel (Leaflet + Google Maps)**
La macro integrada **GenerarMapaANS_Excel()** crea un mapa HTML con:

- Marcadores según estado (verde, amarillo, naranja, rojo, azul)  
- Google Maps de fondo (alta definición)  
- Alternativa OSM (mapa libre)  
- Popups con: pedido, estado, actividad, dirección y subzona  
- Zoom automático al buscar o filtrar actividades  
- Panel lateral con controles  
- Compatible con OneDrive (ruta dinámica)  
- Carga en cualquier equipo sin instalar nada

---

### ✔️ 3. **Macros profesionales integradas**
Incluye módulos VBA para:

- Construcción de HTML dinámico  
- Normalización de direcciones  
- Manejo de íconos Google  
- Filtros de estado  
- Filtros por actividad  
- Zoom automático según número de puntos  
- Limpieza y restablecimiento general del mapa  

El código está optimizado, con comentarios profesionales.

---

## 📂 Estructura de archivos
Plantilla_Dashboard_V5/
│
├── Plantilla.xlsm
├── Plantilla - copia.xlsm # versión de respaldo
└── README.md

---

## 🛠 Requisitos

- **Excel 2016 o superior**  
- Permisos para ejecutar macros (VBA)  
- Conexión a internet si se usa Google Maps como capa base  
- OneDrive habilitado (la macro detecta ruta automáticamente)

---

## 🌐 Tecnologías usadas

- **Excel VBA**  
- **Leaflet.js** (mapas interactivos)  
- **Google Maps Tile Server**  
- **HTML dinámico generado desde macros**  

---

## ⚙️ Configuración rápida

1. Abrir *Plantilla.xlsm*  
2. Habilitar macros  
3. Ir al botón **Generar Mapa ANS**  
4. La macro creará:  
5. El archivo se abrirá automáticamente en el navegador.

---

## 🔐 Privacidad y uso recomendado

- No incluye datos sensibles.  
- Se recomienda usar esta plantilla limpia para portafolio.  
- Si se va a usar con datos corporativos reales, mantener el repositorio privado.

---

## 🧩 Personalización futura

Este repositorio permite evoluciones como:

- Clusterización de marcadores  
- Geocoder automático  
- Capas satelitales híbridas  
- Integración con formularios de Google (evidencias)  
- Visualización de rutas para técnicos  
- Exportación a Power BI  

Si deseas agregar estas funciones, puedo ayudarte a integrarlas.

---

## 👨‍💻 Autor
**Héctor A. Gaviria + IA**  
Dashboard profesional V1 – 2025

---


