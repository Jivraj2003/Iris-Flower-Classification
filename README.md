# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

This project implements a **K-Nearest Neighbors (KNN)** classification model to classify *Iris* flowers based on their **sepal** and **petal** measurements.

---

## 📊 Dataset

The project uses the classic **Iris dataset**, which contains measurements for **150 Iris flowers** from **three species**:

- *Setosa*
- *Versicolor*
- *Virginica*

Each record includes:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 🧱 Project Structure

The Jupyter Notebook is organized into the following sections:

1. **Importing Data and Libraries**  
   - Loads the Iris dataset  
   - Imports required Python libraries

2. **Cleaning Data**  
   - Renames columns for better readability  
   - Checks for and handles missing values  
   - Removes duplicate records

3. **Splitting Data into Training and Testing Sets**  
   - Splits the dataset into training and testing portions  
   - Prepares data for model training and evaluation

4. **Training a Classification Model**  
   - Implements the **K-Nearest Neighbors (KNN)** algorithm  
   - Trains the model using the training data

5. **Testing the Model and Evaluating Accuracy**  
   - Tests the trained model on unseen data  
   - Generates an accuracy score and classification report

6. **Visualizing Data (Matplotlib)**  
   - Uses Matplotlib to plot basic data visualizations

7. **Enhanced Visualization (Seaborn)**  
   - Uses Seaborn to produce more advanced visualizations  
   - Includes a pairplot to visualize relationships between features and species

8. **Conclusion**  
   - Summarizes the results and insights gained from the model

---

## 🛠️ Dependencies

Install the following Python libraries before running the notebook:

```bash
pip install pandas matplotlib seaborn scikit-learn
