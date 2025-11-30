# AgriDashboard - Interactive Flow

Dashboard interaktif untuk analisis area pertanian dengan NDVI (Normalized Difference Vegetation Index).

## 🌾 Fitur

- **Interactive Map** dengan MapTiler SDK
- **Area Selection** - Pilih area pertanian dari peta atau sidebar
- **Calendar Interface** - Pilih tanggal penerbangan drone
- **NDVI Visualization** - Analisis kesehatan tanaman
- **Data Charts** - Visualisasi dengan Chart.js
- **Export Options** - Download PDF, Excel, GeoJSON, Raster

## 🚀 Demo

Dashboard ini dapat diakses langsung tanpa instalasi - buka file `index.html` di browser.

## 📦 Teknologi

- HTML5 / CSS3 / JavaScript
- MapTiler SDK (Map & Satellite Imagery)
- Chart.js (Data Visualization)
- Responsive Design

## 🔑 Setup

File sudah include MapTiler API key. Untuk production, ganti dengan API key Anda sendiri di `index.html`:

```javascript
const MAPTILER_KEY = 'YOUR_API_KEY';
```

## 📱 Preview

Dashboard mencakup 4 step workflow:
1. Pilih Area (dengan interactive map)
2. Pilih Tanggal & Layer
3. Hasil NDVI & Scene Drone
4. Analisis Detail & Export

---

**Created by:** Mohamad Irfan Nurmawan
