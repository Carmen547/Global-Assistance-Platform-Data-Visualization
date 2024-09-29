# Global Assistance Platform - Data Visualization Tool

## Overview
This project visualizes refugee assistance data and uses AI to predict future needs. The dashboard displays trends and AI-driven insights to help governments and NGOs allocate resources effectively.

## Features
- **Data Visualizations:** Explore assistance patterns through interactive visualizations.
- **AI Predictions:** Utilize machine learning to forecast future assistance needs.
- **RESTful API:** Access the data and AI predictions via endpoints.

## Setup
### Dependencies:
- Install the dependencies using `pip install -r requirements.txt`
- Start the Flask app using `python run.py`

### Docker Deployment:
- Build the Docker image: `docker build -t global-assistance .`
- Run the container: `docker run -p 5000:5000 global-assistance`

## Testing
- Run unit tests using `python -m unittest discover tests/`

## Future Improvements
- Integrate real-time data sources for assistance requests.
- Enhance the AI model to handle time-series forecasting.

