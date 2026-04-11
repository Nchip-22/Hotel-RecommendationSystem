# Hotel Recommendation System
A Python-based recommendation engine designed to suggest hotels by analyzing key features such as location, room types, and bed configurations. The system utilizes Content-Based Filtering with Cosine Similarity to provide relevant stay options based on user keywords.

## Key Features
* Data Preprocessing: Handled missing values in review scores using statistical mode and cleaned categorical text data.
* Vectorization: Implemented CountVectorizer to transform hotel descriptions and locations into a mathematical format.
* Similarity Scoring: Applied Cosine Similarity to rank and recommend the top matching hotels.
* Flexible Search: Supports location-based queries to match standard user behavior.

## Tools & Libraries
* Python: Served as the primary programming language for implementing the recommendation logic and data processing workflows.

* Pandas: Utilized for data manipulation, cleaning structured datasets, and managing hotel information efficiently through DataFrames.

* Matplotlib & Seaborn: Employed for exploratory data analysis (EDA) to generate statistical visualizations, such as rating distributions and price-point correlations.

* Scikit-learn: Leveraged for advanced analytical tasks, specifically using CountVectorizer for text feature extraction and cosine_similarity for calculating relationship scores between hotels.

## Methodology
1. Data Cleaning: Categorical features were standardized, and numerical outliers were analyzed.
2. Feature Engineering: A combined Features column was created, integrating location, room category, and bed types to improve recommendation accuracy.
3. Similarity Calculation: Each hotel was represented as a vector, and the distance between these vectors was calculated to determine similarity.
4. Recommendation Engine: A function was developed to accept location or hotel keywords and return the top 5 most similar results.

## How to Run
1. Clone the repository.
2. Ensure the dataset is in the root folder.
3. Run Hotel_Recommendation.ipynb using a Python kernel.