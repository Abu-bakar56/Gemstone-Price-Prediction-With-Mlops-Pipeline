---

# Gemstone Price Prediction With MLOps Pipeline

This project focuses on predicting gemstone prices using a Machine Learning (ML) pipeline, integrated with MLOps practices to ensure smooth deployment and scaling. The model is deployed on [Render](https://gemstone-price-prediction-with-mlops.onrender.com) and can predict the price of gemstones based on various features such as carat, cut, color, clarity, and more.

## Features

- **Data Processing**: Preprocessing, cleaning, and feature engineering for the gemstone dataset.
- **Model Training**: Training the model using machine learning algorithms.
- **MLOps Integration**: CI/CD pipeline for model versioning, automated testing, and deployment.
- **Deployment**: Model deployed on Render for live predictions.
- **Web Interface**: A user-friendly web interface to input gemstone details and get price predictions.
- **Docker Support**: Docker setup for containerized deployment.

## Table of Contents

1. Installation
2. Docker Setup
3. Usage
4. Deployment
5. Video Demo
6. Screenshots
7. Contributing
8. License

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Abu-bakar56/Gemstone-Price-Prediction-With-Mlops-Pipeline.git
   cd Gemstone-Price-Prediction-With-Mlops-Pipeline
   ```
2. Create a virtual environment and install dependencies:
   ```
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```

## Docker Setup

To run the application using Docker, follow these steps:

1. **Build the Docker image**:
   ```
   docker build -t flaskimage .
   ```

2. **Run the Docker container**:
   ```
   docker run -d -p 80:80 flaskimage
   ```

3. **Access the application**:
   Visit `http://localhost:80` in your browser to use the application.

## Usage

1. To run the application locally:
   ```
   python app.py
   ```
2. Access the application in your browser at `http://localhost:5000`.

## Deployment

This project is deployed on Render. Visit the live version here: [Gemstone Price Predictor](https://gemstone-price-prediction-with-mlops.onrender.com)

## Video Demo

Link for video demo: 

https://github.com/user-attachments/assets/452978e1-a5d0-4462-b0cc-7bc8401d400c



## Screenshots and Videos

https://github.com/user-attachments/assets/80555688-4ef6-4e8a-9d93-29e3d1ec758b


![Screenshot 2024-09-10 205315](https://github.com/user-attachments/assets/bbf94a26-73c3-459f-abba-58507af2a426)
![Screenshot 2024-09-10 205229](https://github.com/user-attachments/assets/527ae009-5adb-44a8-94c1-ced2da3614a8)
![Screenshot 2024-09-10 205341](https://github.com/user-attachments/assets/f81e14b8-335e-41f4-a2a3-cf64a26ce49e)



## Contributing

Feel free to submit issues and pull requests if you find any bugs or want to contribute!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---
