# Nissan Puerto Rico — AI Co-Pilot · Historial de Cambios

**Repositorio:** https://github.com/Ricmonpa/nissan.puertorico.git
**Rama:** `main`
**Ruta local:** `C:\Users\maryp\Nissan Copilot`

---

## Fase 2 — Refinamiento Visual (2026-03-24)

### `9f9a605` — 2026-03-24 15:45
**Agrega logo de Nissan para el header**
- Se añadió `nissan-logo.jpg` al proyecto (logo circular Nissan sobre fondo rojo)
- El `<img>` del header ahora lo carga correctamente con fallback en CSS si no existe

---

### `a64fea1` — 2026-03-24 15:42
**Rediseña header al estilo Liverpool: degradado rojo, logo, texto bold**
- Eliminado el badge flotante "NISSAN AI CO-PILOT" que aparecía sobre el video
- Nuevo header con fondo degradado `#C3002F → #8B0020 → #1a0005`
- Logo a la izquierda en cuadro redondeado (`nissan-logo.jpg`)
- Texto a la derecha: título bold en blanco + subtítulo en rojo claro
- Indicador **LIVE** con punto pulsante blanco en la esquina derecha
- Inspirado en el diseño del banner Liverpool Cycling Fest AI

---

### `6d3417d` — 2026-03-24 14:12
**Elimina overlay oscuro sobre el video de fondo**
- Se quitó el `<div class="video-overlay">` que aplicaba un degradado negro semitransparente sobre el video
- El video de fondo ahora se ve con todos sus colores y brillo naturales

---

### `2d8fefc` — 2026-03-24 13:30
**Reemplaza video de fondo y agrega imagen de portada**
- Video `Puerto_Rico_Coastal_Drive_Video.mp4` actualizado con nueva versión generada en **Kling AI** (de 6 MB → 19 MB, mayor calidad)
- Se agregó `interior nissan.jpg` como atributo `poster` del `<video>` para reemplazar el frame inicial automático que venía del video anterior y lucía mal

---

## Fase 1 — Lanzamiento (2026-03-23)

### `777fbe7` — 2026-03-23 14:59
**Launch: Nissan Puerto Rico AI Co-Pilot ad**
- Proyecto base migrado desde el banner Liverpool Cycling Fest AI
- Reemplazado todo el contenido, branding y lógica por Nissan Puerto Rico
- Nuevo video de fondo: `Puerto_Rico_Coastal_Drive_Video.mp4`
- UI rediseñada con colores Nissan (`#C3002F`, negro)
- Chat AI con lógica de intent para Nissan Kicks y Frontier
- Formulario de captura de lead integrado en el flujo del chat

---

## Historial previo — Proyecto Liverpool (2025-12-20 a 2025-12-23)

> Este repositorio originalmente albergó el banner **Liverpool Cycling Fest AI**. Los commits anteriores pertenecen a esa versión del proyecto.

| Hash | Fecha | Descripción |
|------|-------|-------------|
| `6e3fe70` | 2025-12-23 | API Key configurada en Google Cloud con restricciones |
| `24c3ca4` | 2025-12-23 | API Key configurada en Cloudflare Pages Variables Secretas |
| `89b72e7` | 2025-12-23 | SECURITY: Remover API key del checklist, usar placeholders |
| `659a47b` | 2025-12-23 | SECURITY: Remover API key expuesta de documentación |
| `db8db34` | 2025-12-23 | Agrega video de fondo: ciclista en montaña mexicana |
| `dfc1e9b` | 2025-12-23 | Fix: Eliminar requisito de poster y mejorar detección de localhost |
| `29f9257` | 2025-12-21 | Fix: Agregar Referer header al Workers Function |
| `21cb82d` | 2025-12-21 | Agrega guía de remediación GitGuardian |
| `d992bcd` | 2025-12-21 | Remover API key del archivo de auditoría |
| `55b8985` | 2025-12-21 | Auditoría de seguridad: remover todas las API keys |
| `1fc35af` | 2025-12-20 | Remover API key del HTML y agregar proxy Workers |
| `0bb2a31` | 2025-12-20 | Agregar Gemini API Key al head del HTML |
| `d8d617d` | 2025-12-20 | SECURITY: Remover API key expuesta del código |
| `b62dd9a` | 2025-12-20 | Initial commit: Liverpool Cycling Coach AI Banner v1.0.0 |

---

*Generado el 2026-03-24*
