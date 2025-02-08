# Wine Quality Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict the quality of wine using **Machine Learning (Random Forest Classifier)**. The dataset consists of various physicochemical properties of wine that influence its taste and overall quality. By leveraging **Supervised Learning**, we classify wines based on their chemical composition and help in quality assessment.

## 📂 Dataset Information
- **File Name:** `Wine Dataset.csv`
- **Features:**
  - `fixed acidity`: Non-volatile acids affecting taste and stability.
  - `volatile acidity`: High levels can cause an unpleasant vinegar taste.
  - `citric acid`: Enhances wine stability and fresh taste.
  - `residual sugar`: Remaining sugar after fermentation; affects sweetness.
  - `chlorides`: Measures salt content, influencing taste balance.
  - `free sulfur dioxide`: A preservative that prevents oxidation.
  - `total sulfur dioxide`: Sum of free and bound sulfur dioxide.
  - `density`: Related to sugar and alcohol content.
  - `pH`: Determines the acidity level of the wine.
  - `sulphates`: Antimicrobial agent contributing to taste preservation.
  - `alcohol`: Higher alcohol levels often indicate better quality.
- **Target Variable:** `quality` (ranges from 0 to 10, based on sensory analysis)

## 🚀 Project Workflow
1. **Data Preprocessing:**
   - Load the dataset.
   - Handle missing values (if any).
   - Split into features (X) and target (y).
   - Normalize or scale data (if needed).
2. **Model Selection:**
   - Use **Random Forest Classifier** for prediction.
   - Experiment with hyperparameter tuning.
3. **Training & Evaluation:**
   - Train the model using `train_test_split`.
   - Evaluate using **accuracy score** and other metrics.
4. **Feature Importance Analysis:**
   - Determine which features contribute most to wine quality.

## 🛠️ Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/wine-quality-prediction.git
   ```
2. Navigate to the project folder:
   ```sh
   cd wine-quality-prediction
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the project:
   ```sh
   python main.py
   ```

## 📊 Results & Observations
- The model provides an accuracy score of **X%** (tune for better results).
- **Feature Importance Analysis** helps identify which chemical properties contribute most to wine quality.
- Additional improvements can be made by experimenting with other ML models like **SVM, XGBoost, or Neural Networks**.

## 🔥 Future Enhancements
- Implement a **web app** to allow users to input wine characteristics and get quality predictions.
- Perform **hyperparameter tuning** for optimal performance.
- Explore **Deep Learning** techniques to improve accuracy.


