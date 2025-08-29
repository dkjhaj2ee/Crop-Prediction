# Crop Prediction Web App

This project is a web application that predicts the most suitable crop to grow based on soil nutrients and environmental conditions using a machine learning model.

## Features

- Predicts the best crop based on user input (Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall)
- User-friendly web interface built with Flask and Tailwind CSS
- Displays crop recommendations with corresponding images

## Project Structure

```
├── app.py 
├── CropPrediction.ipynb 
├── model.pkl 
├── requirements.txt 
├── ds/ 
│   └── Crop_recommendation.csv 
├── static/ 
│   └── images/ 
│       └── ... (crop images) 
└── templates/ 
    └── index.html
```

## Getting Started

### Prerequisites

- Python 3.10+
- pip

### Installation

1. **Clone the repository:**
   ```sh
   git clone <repo-url>
   cd "Crop Prediction"
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Train or use the model:**
   - The model is trained in `CropPrediction.ipynb` and saved as `model.pkl`.
   - If you want to retrain, run the notebook.

4. **Run the app:**
   ```sh
   python app.py
   ```

5. **Open in your browser:**
   - Go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

## Usage

1. Enter the required soil and environmental parameters in the form.
2. Click "Predict".
3. The recommended crop and its image will be displayed.

## Files

- `app.py`: Flask application code.
- `CropPrediction.ipynb`: Jupyter notebook for data analysis and model training.
- `model.pkl`: Trained machine learning model.
- `ds/Crop_recommendation.csv`: Dataset used for training.
- `templates/index.html`: HTML template for the web interface.
- `static/images/`: Crop images for display.

## Requirements

See `requirements.txt`:

- flask
- pandas
- numpy
- scikit-learn

## License

This project is for educational purposes.