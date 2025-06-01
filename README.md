# Bay Area ZIP Trend Dashboard

This project visualizes home furnishing trends by ZIP code across the Bay Area.

### 🌐 Live Demo:
[View Dashboard on GitHub Pages](https://your-username.github.io/bay-area-zip-dashboard/bay_area_zip_dashboard_with_dropdown.html)

### 📁 Files Included:
- `bay_area_zip_dashboard_with_dropdown.html` – the interactive map dashboard
- `bay_area_zip_trends.geojson` – ZIP code geometries + trend metadata

### 📊 Features:
- Interactive map of all ZIPs across 9 Bay Area counties
- Filter by ZIP, style, and material
- Responsive UI with dynamic map highlighting

### 🔧 How to Use
If you want to view it locally:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000/bay_area_zip_dashboard_with_dropdown.html`

---

Created using Leaflet.js + GeoJSON + Folium for data prep.
