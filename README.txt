# README – Final Project: Classifying Cuisines by Spices

This folder contains all code used in our final project.
All notebooks were developed in Google Colab and exported as .ipynb files.

## Files Overview

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
