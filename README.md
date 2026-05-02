# MU Online S3 — Project Dashboard

Dashboard de gestión personal para el desarrollo de un servidor privado de **MU Online Season 3 Episodio 2** corriendo sobre el engine **Louis Emulator Update 42** (base Season 6 con downgrade visual a S3).

## ¿Qué es esto?

Una herramienta HTML single-file que uso para:

- 📋 **Trackear el cronograma** de desarrollo en 4 etapas (compra de licencia → setup → beta → grand opening)
- ⚙️ **Documentar configuraciones** del servidor (archivos `.dat` y `.txt` del Louis Emulator)
- 📝 **Tomar notas** sobre sistemas a usar, cuáles no, y qué ya está configurado
- 📦 **Consultar el historial** de updates del emulador (update 1 al 42) con sus features y variables

## Características

### Secciones

| Tab | Contenido |
|-----|-----------|
| 📋 Proyecto S3 | Overview, Cronograma 4 meses, Infraestructura, Equipo, Monetización |
| ⚙️ Louis Emulator Files | Updates 1-42, Server Config, Cliente, Seguridad, Eventos, Offline Systems, Economía, Discord |
| ⭐ Recomendaciones | Qué usar y qué evitar para tu servidor S3 |

### Funcionalidades

- ✅ **Checkboxes de progreso** por cada tarea/configuración
- 📝 **Notas por card** persistidas en `localStorage`
- 🔍 **Búsqueda global** y filtros por estado (pendiente/wip/done/skip) y tipo (server/client)
- ⚡ **Filtro "Solo pendientes"** para enfocarse en lo que falta
- 📤 **Exportar notas** como `.txt` con todas las notas escritas
- ⧉ **Botón Copiar** en cada code block de configuración
- 📊 **Contador de progreso** en sidebar por sección (done/total)
- 💾 **Autosave** cada 30 segundos con indicador visual

## Tech Stack

- Single-file HTML — sin dependencias externas ni npm
- CSS vanilla con variables custom (tema RPG oscuro)
- JavaScript vanilla (sin frameworks)
- `localStorage` para persistencia
- Google Fonts: Cinzel + Nunito + JetBrains Mono
- Funciona 100% offline una vez cargada

## Concepto del Servidor

**Engine:** Louis Emulator Update 42 (Season 6 base)  
**Visual:** Season 3 Episodio 2 con downgrade de assets  
**Rates:** 100x EXP · Medium-Slow · Sin MuHelper  
**Clases:** DK, DW, FE, MG, DL + Summoner como clase especial (requiere Quest)  
**Monetización:** VIP + XShop cosmético/consumible — **Sin P2W**  
**Infraestructura:** VPS OVH São Paulo · Anti-DDoS Game  

---

> Single-file HTML dashboard, no dependencies, works offline.
