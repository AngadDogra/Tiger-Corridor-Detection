# Tiger Corridor Detection Using K-Means Clustering

## Project Overview

The **Tiger Corridor Detection** project aims to identify and optimize corridors used by tigers to traverse different regions. This work combines population trend analysis, geospatial mapping, and machine learning techniques to ensure conservation efforts are targeted and effective.

### Goals
- **Population Analysis**: Understand the historical trends in tiger populations.
- **Corridor Mapping**: Use geographical data to identify and visualize tiger movements.
- **Corridor Optimization**: Apply the K-Means clustering algorithm to optimize the detection of tiger corridors for better conservation planning.

---

## Dataset

1. **Tiger Population Data**:
    - Collected from various sources, this dataset contains tiger population statistics over several years.
    - Features include year, region, and population size.
  
2. **Geospatial Data**:
    - Latitude and longitude data of tiger populations across regions.
    - Shapefiles used for mapping protected areas and known corridors.

---

## Methodology

### 1. **Population Trend Analysis**
We began by analyzing tiger population trends over the years using data visualization techniques. Graphs were plotted to show fluctuations in population, helping to identify key regions where conservation efforts may need to be intensified.

### 2. **Mapping Tiger Populations**
- Using shapefiles and the geospatial coordinates (latitude and longitude) of tiger populations, we plotted maps to visualize the distribution of tiger populations across different regions.
- These maps allowed us to identify clusters of tiger populations and better understand movement patterns.

### 3. **Corridor Detection with K-Means**
- To optimize tiger corridor detection, we used the **K-Means clustering algorithm**.
- The goal was to group similar regions where tiger movement is concentrated, thus identifying natural corridors.
- This clustering allowed us to pinpoint the areas that require corridor optimization to facilitate safe passage for tigers between habitats.

---

## Results

- **Population Trends**: Visualization of tiger population trends showed significant decreases in some areas, guiding us on where to focus future efforts.
- **Corridor Mapping**: Our maps illustrated tiger habitats and movement patterns, forming a basis for detecting corridors.
- **Optimized Corridors**: K-Means clustering identified optimal tiger corridors, allowing us to propose regions where conservation and wildlife protection measures should be prioritized.

---

## Future Work

- **Advanced Machine Learning**: We plan to explore more sophisticated models such as DBSCAN for detecting irregular-shaped corridors.
- **Data Collection**: More recent and comprehensive data will improve the accuracy of our corridor detection models.
- **Integration with Wildlife Monitoring**: Collaborating with camera trap systems to get real-time data on tiger movements and adjust corridors dynamically.

---

## How to Run the Project

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/tiger-corridor-detection.git
    cd tiger-corridor-detection
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the data analysis and K-Means clustering:

    ```bash
    python tiger_corridor_analysis.py
    ```

4. View the results:

    Output maps and plots will be saved to the `results` directory.

---

## Dependencies

- Python 3.7+
- Pandas
- Matplotlib
- Geopandas
- Scikit-learn (for K-Means)
- Shapely (for working with shapefiles)

---

## Contributors

- Chanchreek Jain 
- Angad Dogra

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
