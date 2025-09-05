Mangrove-Health-Classification-with-Sentinel-2-and-ML

🌱 Mangrove Health Classification using Sentinel-2 satellite imagery and machine learning techniques to monitor, assess, and predict the condition of mangrove ecosystems. This project combines remote sensing, geospatial analytics, and predictive modeling to support conservation and climate resilience strategies.

🚀 Project Overview

Mangroves play a critical role in coastal protection, biodiversity, and carbon sequestration. However, they are threatened by deforestation, climate change, and human activities.
This project leverages Sentinel-2 multispectral bands and machine learning classifiers (Random Forest, SVM, Gradient Boosting, etc.) to:

Detect healthy vs degraded mangrove zones.

Identify stress indicators through spectral signatures.

Support long-term mangrove monitoring with reproducible workflows.

📂 Repository Structure
├── data/                  # Sample Sentinel-2 datasets (links or instructions)
├── notebooks/             # Jupyter notebooks for preprocessing & ML training
├── src/                   # Python source code for data processing & models
├── models/                # Saved trained models
├── results/               # Classification maps & performance metrics
├── requirements.txt       # Dependencies
└── README.md              # Project documentation

🔑 Features

Preprocessing pipeline for Sentinel-2 (cloud masking, atmospheric correction).

Spectral indices (NDVI, NDWI, MSI) for mangrove health analysis.

Machine learning classification for healthy vs stressed/degraded zones.

Evaluation metrics (accuracy, F1-score, confusion matrix).

Export of results in GeoTIFF and shapefile formats.

⚙️ Installation

Clone the repository and install dependencies:

git clone https://github.com/yourusername/Mangrove-Health-Classification-with-Sentinel-2-and-ML.git
cd Mangrove-Health-Classification-with-Sentinel-2-and-ML
pip install -r requirements.txt

🛰️ Data Sources

Sentinel-2 L2A imagery (10–20 m resolution) → Copernicus Open Access Hub

Shapefiles / AOI boundaries (local mangrove extent shapefile from Global Mangrove Watch
)

🧑‍💻 Usage

Preprocess data:

python src/preprocess.py --input data/sentinel2_raw/ --output data/processed/


Train classifier:

python src/train_model.py --data data/processed/ --model models/rf.pkl


Run classification:

python src/classify.py --model models/rf.pkl --input data/processed/ --output results/

📊 Results

Health classification maps (healthy, stressed, degraded).

Model accuracy >85% in test AOIs.

Time-series analysis to track mangrove degradation trends.

🌍 Applications

Coastal ecosystem management.

Climate adaptation and mitigation projects.

Blue carbon monitoring for carbon credit initiatives.

Early warning systems for mangrove degradation.

🤝 Contributing

Contributions are welcome! Please fork this repo, create a feature branch, and submit a pull request.

📜 License

This project is licensed under the MIT License. See LICENSE
 for details.

📧 Contact

Maintainer: Amos Meremu Dogiye
Github: https://github.com/Dogiye12
📩 Email:

🔗 LinkedIn: https://www.linkedin.com/in/meremu-amos-993333314/
