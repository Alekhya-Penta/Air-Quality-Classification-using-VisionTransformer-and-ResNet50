# Air-Quality-Classification-using-VisionTransformer-and-ResNet50

Air pollution is a major environmental and public health concern, linked to respiratory and cardiovascular diseases. Traditional air quality monitoring relies on ground sensors and statistical models, which are costly, time-consuming, and labor-intensive. Deep learning models like CNNs, Transformers, and hybrids improve air quality classification but face challenges like high computational complexity and poor generalization. To address these issues, we propose a Hybrid ViT-ResNet50 model, combining ResNet50's spatial feature extraction with ViT's global attention for enhanced accuracy and robustness. Using an air pollution image dataset from India and Nepal, the ViT-ResNet50 model outperforms ViT, ResNet50, and CNN-LSTM. This confirms its effectiveness for air quality classification, making it a promising solution for real-time and scalable air quality monitoring.

# Data Collection

The Dataset is obtained from Kaggle.
This dataset contains images of Air Pollution for different cities in India and Nepal. The dataset is divided into two folders: Combined_Dataset and Country_wise_Dataset.
Total number of image dataset: 12,240 Image size: 224*224
Air Quality Index (AQI) Class and its defination used in the dataset.
There are a total of six classes of Air Pollution, which we represent in our dataset as follows:
1. Good (0-50): Air quality is considered satisfactory and air pollution poses little or no risk.
2. Moderate (51-100): Air quality is acceptable; however, for some pollutants, there may be a moderate health concern for a very small number of people who are unusually sensitive to air pollution.
3. Unhealthy for Sensitive Groups (101-150): Members of sensitive groups may experience health effects, but the general public is unlikely to be affected.
4. Unhealthy (151-200): Some members of the general public may experience health effects; members of sensitive groups may experience more serious health effects.
5. Very Unhealthy (201-300): Health alert: The risk of health effects is increased for everyone.
6. Hazardous/Severe (301-500): Health warning of emergency conditions: Everyone is more likely to be affected.
Reference :
https://www.kaggle.com/datasets/adarshrouniyar/air-pollution-image-dataset-from-india-and-nepal
