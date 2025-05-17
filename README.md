# Field Cropped Area Map

This simple web map shows **cropped vs uncropped (fallow)** areas within agricultural fields, using time-series satellite imagery analysis.

🔗 **Live Map**: [Click to view](https://goswamishreyas.github.io/Field_cropped_area_/)

For testing, an area was selected where **actively cropped fields** and **fallow lands** lie **next to each other**. This clear spatial contrast helps evaluate the effectiveness of crop detection from satellite data.

---

## 🛰️ About

This project demonstrates how **Sentinel-2 time series imagery** can be used to identify cropped and uncropped areas within fields.

- The example AOI (Area of Interest) includes neighboring **cropped and fallow** plots.
- A simple map interface built with **Leaflet** allows visualization of:
  - Cropped areas (in green)
  - Field boundaries (in yellow)
- Hovering over boundaries shows the percentage of cropped area in each field.

---

## 🌱 Why This Matters

Mapping cropped and uncropped areas within agricultural fields is crucial for:

- **Planning input distribution** (fertilizer, irrigation, seed).
- **Detecting underutilized or fallow land** for potential improvement.
- **Verifying field activity** in large-scale agricultural programs and subsidies.

By using satellite-based time series data, such maps can be generated across large areas at low cost and high frequency.

