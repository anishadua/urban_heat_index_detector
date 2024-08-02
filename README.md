Urban Heat Index Detector

This project is a comprehensive Urban Heat Index Detector designed to analyze and visualize heat index data in urban areas. It utilizes machine learning models and geospatial data to assess and monitor heat distribution.

Features
Data Processing: Handles geospatial and temperature data for heat index analysis.
Model Integration: Utilizes machine learning models for predictive analytics.
Visualization: Provides visual representations of heat distribution using folium and streamlit.
Interactive Web Application: Built with Streamlit for interactive data exploration and visualization.

Installation
To set up the project locally, follow these steps:

Clone the Repository
git clone https://github.com/anishadua/urban-heat-index-detector.git
cd urban-heat-index-detector
Set Up the Environment

It's recommended to use a virtual environment. You can set it up using venv or conda.

Using venv:

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Using conda:
bash
Copy code
conda create --name uhi_detector python=3.10
conda activate uhi_detector
Install Dependencies
pip install -r requirements.txt
Usage
To run the application, use the following command:
streamlit run app.py
This will start a local server and open the application in your web browser.
