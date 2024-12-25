# CoaSight: Accessible Shoreline Change Analysis

CoaSight is a user-friendly tool designed to empower coastal communities with actionable insights into shoreline erosion. By leveraging satellite data and advanced image processing, CoaSight provides clear risk assessments, historical trends, and future predictions to help individuals, farmers, and small businesses make informed decisions.

## Features

- **Clear Risk Assessments**: Input a location to receive a detailed risk score showing how erosion may impact homes, farms, or businesses.
- **Trends and Predictions**: Visualize how shorelines have shifted over time and predict future changes to enable proactive planning.
- **Interactive Maps and Graphs**: Explore erosion trends and at-risk zones with intuitive visuals.
- **Practical Advice**: Get tailored recommendations for mitigating erosion risks.

## How It Works

1. **Satellite Data Collection**:
   - Uses **Google Earth Engine** to extract Sentinel-2 imagery of coastal areas.
   - Filters images with less than 20% cloud coverage for clarity.
2. **Image Processing**:
   - Converts GeoTIFF images to JPG using **Rasterio** and **NumPy** for easier handling.
3. **Shoreline Detection**:
   - Employs **Canny Edge Detection** in **OpenCV** to identify the land-water boundary.
4. **Change Measurement**:
   - Tracks X/Y position shifts, total land depletion, and annual retreat rates.
5. **Data Visualization**:
   - Generates graphs and overlay maps with **Matplotlib** to highlight long-term erosion trends.
6. **Future Predictions**:
   - Forecasts shoreline positions up to 2030 based on historical trends.

## Technologies Used

- **Google Earth Engine**: Satellite imagery extraction and preprocessing.
- **OpenCV**: Shoreline detection using Canny Edge Detection.
- **Rasterio** and **NumPy**: Image standardization and processing.
- **Matplotlib**: Graphs and visual overlays for data interpretation.
- **Python**: Core programming language for analysis and modeling.

## Why CoaSight?

CoaSight bridges the gap between technical shoreline data and practical decision-making for non-experts. By transforming complex datasets into accessible, actionable insights, CoaSight empowers communities to safeguard their coastlines against erosion and environmental risks.

---

Explore the repository to see how CoaSight is making a difference in coastal resilience! 🌍
