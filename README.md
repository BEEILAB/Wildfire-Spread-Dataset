# A Deep Learning-Based Dataset to Predict Wildfire Spread from Remote Sensing Data: Integrating Landsat Satellite Data and Environmental Variables

**Authors:** [Mohammad Marjani](https://www.linkedin.com/in/mohammad-marjani-727547206/), [Dr. Masoud Mahdianpari](https://www.mun.ca/engineering/about/our-people/masoud-mahdianpari/), Dr. Fariba Mohammadimanesh

Wildfires pose significant threats to ecosystems, communities, and economies and have shown a significant increase in frequency and intensity in recent years. Accurate wildfire spread prediction is critical for efficient management and mitigation strategies. Due to the limitations of current wildfire spread datasets, this study introduces a novel wildfire spread dataset for Alberta, Canada, covering wildfire events from 2001 to 2019. The dataset incorporates Landsat 7 (L7) and Landsat 8 (L8) data at 30-meter spatial resolution and daily environmental variables at 250-meter resolution, providing finer spatial and temporal detail than existing datasets. Integration of residual neural network (ResNet) and DeepLabV3 were used as a baseline for wildfire spread prediction based on the generated dataset, and its performance was evaluated using key metrics, such as precision, recall, F1-score (F1), and area under curve (AUC). Results indicate moderate success in identifying burned pixels with balanced precision and recall. The flexibility of the dataset's format also opens possibilities for applying advanced models, such as transformers, to enhance prediction capabilities further. This research advances wildfire spread prediction by addressing critical limitations in current datasets and providing a foundation for more sophisticated modeling approaches.


# Constant Variables
Constant variables include remote sensing data with higher resolution, such as the Normalized Difference Vegetation Index (NDVI), Normalized Difference Built-up Index (NDBI), and Normalized Difference Water Index (NDWI), collected from Land sat 7 and Landsat 8 satellites. The order of bands in constant variables is:
- **Band 1: NDBI**
- **Band 2: NDVI**
- **Band 3: NDWI**
- **Band 4: DEM**
- **Band 5: Slope**
  
![Constant_github](https://github.com/user-attachments/assets/5aa1e8fc-450d-4f1c-8b12-f65a4882d3c9)


# Daily Variables
Daily variables were collected with a daily temporal resolution, providing detailed information on environmental conditions affecting wildfire spread. The dataset includes the following daily variables:

- **Surface Pressure (SP)**: Atmospheric pressure at the surface level.
- **Precipitation**: Amount of rainfall or snowfall.
- **Maximum Surface Net Solar Radiation (SNSR)**: Solar radiation reaching the surface.
- **Soil Temperature Level 1 (STL1)**: Temperature of the soil at a specific depth.
- **Leaf Area Index for High Vegetation (LAIHV)**: Area of leaves per unit ground area for high vegetation.
- **Skin Temperature (ST)**: Temperature at the Earth's surface.
- **Runoff**: Water flow that occurs when soil is saturated or impervious.
- **Leaf Area Index for Low Vegetation (LAILV)**: Area of leaves per unit ground area for low vegetation.
- **Dew Point Temperature at 2 Meters Above the Surface (DT2m)**: Temperature at which air becomes saturated with moisture.
- **Energy Release Component (ERC)**: Potential energy available for combustion.
- **Wind Direction (WD)**: Direction from which the wind is blowing.
- **Wind Speed (WS)**: Speed of the wind.
- **MODIS NDVI**: Normalized Difference Vegetation Index from MODIS data.

![image](https://github.com/user-attachments/assets/ac9f5b6c-3b60-479e-a8b5-6dd935430e8f)

## Data Availability

The dataset used in this study is available for download at the following link:

[Download Wildfire Spread Dataset](your-download-link-here)

This dataset includes three folders:
- **Input (Constant)**: Contains constant variables such as NDBI, NDVI, NDWI, DEM, and Slope.
- **Input (Daily)**: Contains daily variables such as Surface Pressure (SP), Precipitation, Maximum Surface Net Solar Radiation (SNSR), Soil Temperature Level 1 (STL1), Leaf Area Index for High Vegetation (LAIHV), Skin Temperature (ST), Runoff, Leaf Area Index for Low Vegetation (LAILV), Dew Point Temperature at 2 Meters Above the Surface (DT2m), Energy Release Component (ERC), Wind Direction (WD), Wind Speed (WS), and MODIS NDVI.
- **Label**: Contains files corresponding to the labels for the wildfire spread predictions.

Each folder contains a file that corresponds to those in the other two folders.



## Contact
For any questions or issues, please open an issue in the repository or contact the authors at [mmarajni.@mun.ca](mailto:mmarajni.@mun.ca).

## Citation
If you use this dataset in your research, please cite the following paper:

```bibtex
@article{your_paper,
  title={A Deep Learning-Based Dataset to Predict Wildfire Spread from Remote Sensing Data: Integrating Landsat Satellite Data and Environmental Variables},
  author={Your Name and Co-Authors},
  journal={Journal Name},
  year={2024},
  volume={X},
  pages={X-Y},
  doi={XX.XXXX/XXXXXX}
}



