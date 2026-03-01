# Data Mining Project: Classifying Cuisines by Spices 🌶️  

This repository contains the full codebase and analysis for our project.  

**🔗 [Read our Full Analysis Report Here](Spice_Analysis_Writeup.pdf)**

---

## Project Overview  

Our research focuses on identifying the unique "culinary fingerprint" of world cuisines by analyzing global spice patterns and building machine learning models to predict a dish's origin based on its ingredients.  

### Key Milestones
* **Data Collection:** Crawling and parsing thousands of recipes from AllRecipes.
* **Network Analysis:** Identifying "communities" of spices that define regional cooking.
* **Machine Learning:** Training classifiers to distinguish between global cuisines.

### Notebooks & Workflow

All analysis was developed in `Google Colab` notebooks and exported as .ipynb files.  

The project follows a structured pipeline:  

1. **global_spice_consumption.ipynb**
   Visualizes worldwide spice consumption trends based on FAOSTAT dataset.

2. **create_spice_map.ipynb**
   Builds the 'spice_map': a dictionary mapping each spice to a list of its alternative names.

3. **crawling_recipes.ipynb**
   Crawls recipes from AllRecipes using the sitemap, extracts their data, and identifies spices within each recipe using the spice_map.

4. **spices_community_analysis.ipynb**
   Network analysis of spices using co-occurrence in recipes, and applies community detection to identify spice clusters.

5. **models.ipynb**
   Trains and evaluates ML models (Logistic Regression, Random Forest) for cuisine classification, including performance metrics and visualizations.

## Technologies Used
* **Languages:** Python (Jupyter Notebooks)
* **Libraries:** Pandas, NumPy, Scikit-learn
* **Visualization:** Matplotlib, Seaborn, NetworkX
* **Data Sources:** FAOSTAT, AllRecipes.com

