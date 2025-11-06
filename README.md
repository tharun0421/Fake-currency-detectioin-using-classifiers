# Fake Currency Detection
A machine learning and image processing project designed to detect counterfeit currency notes by analyzing images for authenticity. The goal is to automate fake note identification using extracted visual and statistical features.

# Project Overview
Tackles the problem of counterfeit currency using advanced detection techniques.
Processes note images to separate real from fake using multiple models.

# Exploratory Data Analysis (EDA)
Analyses distribution of real vs. fake note images.
Visualizes pixel intensity, image dimensions, and class balance.
Includes image sampling and histogram analysis to uncover patterns and outliers.

# Methodology
Image Acquisition: Collects and labels currency note images.

Preprocessing: Converts images to grayscale, normalizes pixel values, standardizes size, removes noise, and augments data for robustness.

Feature Engineering: Extracts relevant features (texture, watermark, security thread, micro-text) using statistical and machine vision methods.

Model Building: Tests algorithms such as Decision Tree, Random Forest, SVM, and KNN for classification.

Evaluation: Uses accuracy, precision, recall, and F1-score metrics to assess model performance and ensure robust predictions.

Future Scope
Adaptive models that evolve with new counterfeiting methods.

Enhanced collaboration for better dataset variety.

Integration with banking and retail point-of-sale systems.
