# Agricultural Suitability Index Dataset (suit.tif)

This dataset contains a time-varying index for agricultural suitability across Europe from 1500 to 2000. The index is designed to quantify the suitability of land for agricultural use based on climatic and soil factors, such as temperature, precipitation, soil pH, and carbon content. It is calculated using a simple surface energy and water balance model, with a grid resolution of 0.5° x 0.5°, and is available for each year within the given period. The dataset enables researchers to explore the influence of climate fluctuations on Europe's agricultural landscape and to study historical dynamics related to climate and society.

The data was generated using reconstructed historical temperature and precipitation datasets and incorporates soil characteristics such as carbon content and pH to assess suitability for crops like wheat, rye, barley, and oats in pre-industrial Europe.

## Data Dictionary Table

| Variable Name         | Description                                                                                              |
|-----------------------|----------------------------------------------------------------------------------------------------------|
| `Agricultural Suitability Index` | A continuous variable representing the likelihood of land being suitable for cultivation. Values range from 0 (unsuitable) to 1 (highly suitable). |
| `Latitude`            | Latitude coordinate for each grid cell in the raster dataset.                                             |
| `Longitude`           | Longitude coordinate for each grid cell in the raster dataset.                                            |
| `Growing Degree Days (GDD)` | A measure of cumulative temperature exposure, used to assess the growing season for crops. Calculated using daily temperature data. |
| `Aridity Index (AI)`  | A measure of soil moisture, calculated using precipitation and potential evapotranspiration data.         |
| `Soil pH`             | pH level of the topsoil (0-30 cm), which impacts nutrient availability and crop growth.                   |
| `Soil Carbon Content` | The amount of carbon in the topsoil (0-30 cm), influencing soil fertility and water retention.            |
| `Precipitation`       | Historical annual precipitation values, given in millimeters.                                             |
| `Temperature`         | Historical annual temperature values, given in degrees Celsius.                                           |

