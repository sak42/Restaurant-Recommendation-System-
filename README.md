# Restaurant-Recommendation-System-
Restaurant Recommendation System
screenshots
![image alt](https://github.com/sak42/Restaurant-Recommendation-System-/blob/eafe8d119e9fccc6d4bef1c9d62eb7d46a6dfc85/r1.png)
input  
![image alt](https://github.com/sak42/Restaurant-Recommendation-System-/blob/2a7c12da4637e6f62a84991d3475eaf2cd92852b/input%20page.png)
output 
![image alt](https://github.com/sak42/Restaurant-Recommendation-System-/blob/aa2d8ff9c58796ebc21bcedd77b7bdc7fc61560f/output.png)
Installation and Setup
Using Conda (Recommended)
# Create a new conda environment
conda create -n restaurant_recommender python=3.10

# Activate the environment
conda activate restaurant_recommender

# Install dependencies
pip install -r requirements.txt
Using Python venv
# Create a virtual environment
python -m venv venv

# Activate the environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
Running the Application
# Navigate to the Flask directory
cd Flask

# Run the Flask web application
python app.py

structure
Restaurant-Recommendation-System/
├── Documentation...
├── Flask/
│   ├── __pycache__/                # Compiled Python cache files
│   ├── static/                     # Static assets (Images)
│   ├── templates/                  # HTML templates for the frontend
│   ├── app.py                     # Flask application entry point
│   ├── Final_Development_Phase.ipynb  # Flask dev notebook
│   ├── requirements.txt            # Python dependencies
│   └── restaurant.csv             # Restaurant dataset
├── Model/
    └── Final_Development_Phase.ipynb  # Model training and evaluation notebook
