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

Technologies Used


Python 3.10 – Core programming language
Flask – Lightweight web framework to build the backend API
Scikit-learn – For building and evaluating machine learning models
Surprise – Specialized library for collaborative filtering (e.g., SVD)
Pandas / NumPy – For data manipulation and preprocessing
NLTK – For natural language processing and cleaning review text
Matplotlib / Seaborn / Plotly – For data visualization and EDA
HTML / CSS / JavaScript – For designing the frontend interface


Model Architecture
This project uses a Hybrid Recommendation Model combining the strengths of:

🔹 Content-Based Filtering

Analyzes restaurant attributes like cuisine type, average cost, rating, and delivery option.
Matches these with user-stated preferences to recommend relevant restaurants.
🔹 Collaborative Filtering (SVD)

Uses historical user rating data to find similar users and suggest restaurants based on collective behavior.
Implemented using the Surprise library's Singular Value Decomposition (SVD) algorithm.
🔹 Hybrid Approach

Merges both filtering strategies to solve the cold-start and sparsity problems.
Balances personalization with discovery of new or less popular options.


Dataset
The dataset is sourced from Kaggle and titled:
Zomato Bangalore Restaurants Dataset by Himanshu Poddar

Conclusion
This project successfully demonstrates how machine learning and recommendation systems can simplify dining decisions by tailoring restaurant suggestions to user preferences and behavior. It offers a powerful and adaptive solution for users in both familiar and unfamiliar areas. The hybrid model ensures balance between personalized results and discovery of new options. This project lays the foundation for more advanced, real-time, and location-aware food recommendation engines.
