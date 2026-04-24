# notsure KML/KMZ Map Viewer

## 🗺️ Descripción del Proyecto

**notsure KML/KMZ Map Viewer** es una aplicación web geoespacial para la visualización interactiva de archivos **KML** y **KMZ** directamente en el navegador. Construida con **Leaflet**, **Bootstrap 5** y **OpenStreetMap** como base cartográfica, sin dependencia de Google Maps.

Este proyecto se desarrolla **en paralelo** como una rama independiente, tomando como punto de partida el trabajo original de [xsukax/xsukax-KML-KMZ-Map-Viewer](https://github.com/xsukax/xsukax-KML-KMZ-Map-Viewer). El crédito por la arquitectura base y el diseño inicial corresponde a **xsukax**.

El mapa se inicializa por defecto en **Río Gallegos, Santa Cruz, Argentina**.

---

## 🙏 Basado en

Este proyecto está basado en:

> **[xsukax/xsukax-KML-KMZ-Map-Viewer](https://github.com/xsukax/xsukax-KML-KMZ-Map-Viewer)**
> por [xsukax](https://github.com/xsukax) — Licencia GPL-3.0

notsure es un fork independiente que mantiene la misma filosofía: 100% client-side, sin backend, sin rastreo.

---

## 🔒 Privacidad y Seguridad

* **Procesamiento local:** Los archivos nunca se envían a ningún servidor.
* **Sin almacenamiento externo:** Los datos permanecen en memoria local durante la sesión.
* **Código abierto:** Auditable en su totalidad.
* **Dependencias confiables:** Leaflet, JSZip y toGeoJSON, cargados por HTTPS desde CDNs oficiales.

---

## ⚙️ Características

* Visualización instantánea de `.kml` y `.kmz`
* Extracción automática de KML desde archivos KMZ (via JSZip)
* Tooltips, popups e inspección de metadatos por feature
* UI responsiva con Bootstrap 5 y Animate.css
* Mapa base: OpenStreetMap (sin Google Maps)
* Un solo archivo `index.html` — sin build, sin dependencias locales

---

## 💻 Instalación

```bash
git clone https://github.com/nitsugaone/notsure-KML-KMZ-Map-Viewer.git
cd notsure-KML-KMZ-Map-Viewer
open index.html
```

---

## 🚀 Uso

1. Abrir `index.html` en el navegador (o acceder via GitHub Pages)
2. Hacer clic en **"Select KML/KMZ File"** o arrastrar el archivo
3. El mapa renderiza los features automáticamente
4. Hacer clic en cualquier feature para ver sus metadatos
5. **"Clear Map"** para limpiar y reiniciar

---

## 🌍 Demo

[https://nitsugaone.github.io/notsure-KML-KMZ-Map-Viewer/](https://nitsugaone.github.io/notsure-KML-KMZ-Map-Viewer/)

---

## 🧾 Licencia

GPL-3.0 — ver [LICENSE](./LICENSE)

---

## 👤 Autor

**nitsugaone** — [OpenStreetMap](https://www.openstreetmap.org/user/nitsugaone) · [GitHub](https://github.com/nitsugaone)
