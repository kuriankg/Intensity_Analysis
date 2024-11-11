# Intensity_Analysis
Objective: Develop an NLP-based model to predict the intensity of emotions in text reviews.
Data Import: Load datasets of text reviews for different emotions (angriness, happiness, sadness).
Data Integration: Combine datasets into a single DataFrame for unified processing.
Label Encoding: Transform the intensity labels into numeric values using LabelEncoder.
Data Splitting: Divide the data into training and test sets (80-20 split).
Pipeline Setup: Build an NLP pipeline that includes text vectorization and classification.
Vectorization: Use TfidfVectorizer to convert text reviews into a matrix of TF-IDF features.
Model Selection: Choose LogisticRegression as the classification algorithm within the pipeline.
Model Training: Train the pipeline on the training dataset.
Evaluation: Predict on the test set and evaluate using accuracy and a classification report.
Cross-Validation: Perform cross-validation to assess model stability across folds.
Model Persistence: Save the trained model pipeline using joblib for future use
