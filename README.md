# Coasight: Shoreline Change Analysis Using Satellite Imagery

Coasight is a Python-based project that analyzes shoreline changes over time using Sentinel-2 satellite imagery. The project employs advanced image processing techniques and geospatial tools to monitor coastal erosion and forecast future shoreline positions, supporting sustainable coastal management efforts.

## Key Features

- **Satellite Data Processing**:
  - Utilized **Google Earth Engine** to filter Sentinel-2 imagery with less than 20% cloud cover and generate RGB composites for analysis.
- **Shoreline Detection**:
  - Applied **OpenCV's Canny Edge Detection Algorithm** to identify shoreline boundaries in satellite images.
- **Data Analysis**:
  - Calculated retreat rates, average shoreline positions, and percentage changes across multiple time periods.
  - Forecasted future shoreline positions using historical trend analysis.
- **Visualization**:
  - Created overlay maps and visualized shoreline changes over time using **ArcGIS** and Python-based plotting libraries.

## Technologies Used

- **Python**: Core programming language for data processing and analysis.
- **Google Earth Engine**: For satellite imagery filtering and composite generation.
- **OpenCV**: For edge detection and shoreline boundary extraction.
- **ArcGIS**: For advanced geospatial visualization.
- **Matplotlib & NumPy**: For data visualization and statistical analysis.

## Results

- Successfully quantified shoreline retreat rates and forecasted changes with high accuracy.
- Developed visual overlays to highlight shoreline changes across years, aiding in understanding erosion patterns.

## Usage

To replicate the analysis, you will need:
1. Access to **Google Earth Engine** for Sentinel-2 imagery.
2. Python environment with the following libraries installed:
   - `OpenCV`
   - `NumPy`
   - `Matplotlib`
3. Optional: Access to **ArcGIS** for enhanced geospatial visualization.

## Future Work

- Extend the analysis to additional coastal regions globally.
- Integrate machine learning models for automated erosion pattern prediction.

---

Feel free to explore the code and contribute to improving Coasight! 🌍
