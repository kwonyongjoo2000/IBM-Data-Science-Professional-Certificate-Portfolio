# Rocket Science with Data: Predicting SpaceX's Landing Success

## Objective

This project, conducted for SpaceY, aimed to analyze the factors driving SpaceX’s success in rocket landings, leveraging data science techniques to uncover actionable insights. By identifying key variables influencing landing outcomes, the goal was to guide SpaceY in optimizing their own rocket recovery strategies, reducing costs, and becoming a viable competitor in the aerospace industry.

## Data Science Methodology

### 1. Data Collection:
Leveraged the SpaceX REST API and web scraping techniques to gather relevant data on rocket launches, including details on payloads, launch sites, and mission destinations.

### 2. Data Preprocessing: 
Cleaned and transformed the dataset using Pandas and NumPy, applying techniques such as One-Hot Encoding, normalization, and standardization to ensure model readiness.

### 3. Exploratory Data Analysis (EDA):
Conducted an in-depth EDA using Seaborn and Matplotlib to visualize key trends and relationships in the data. SQL was used for efficient querying and data manipulation.

### 4. Interactive Visual Analytics:
Developed interactive maps and dashboards using Folium and Plotly Dash, enabling stakeholders to explore the spatial distribution of launch sites and landing outcomes.

### 5. Predictive Modeling: 
Built and tuned classification models to predict successful rocket landings. After experimenting with various algorithms, hyperparameter tuning via Grid Search identified the most effective model for deployment.

## Conclusion and Implications

The analysis revealed that variables such as launch site, payload type, and mission trajectory play a critical role in determining landing success. The final classification model, which was fine-tuned for maximum accuracy, provided reliable predictions for future landings. These insights equip SpaceY with the knowledge to refine its rocket recovery operations, significantly reducing launch costs and enhancing competitiveness in the aerospace sector.
