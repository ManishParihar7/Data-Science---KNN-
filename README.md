# Data-Science---KNN
# Glass Classification with K-Nearest Neighbors (KNN)

## Problem

Implement a KNN model to classify different types of glass based on their characteristics.

## Data Description

The dataset contains the following features:

- RI: Refractive index
- Na: Sodium
- Mg: Magnesium
- Al: Aluminum
- Si: Silicon
- K: Potassium
- Ca: Calcium
- Ba: Barium
- Fe: Iron

The target variable is "Type," representing different types of glass.

## Project Structure

The project is organized as follows:

- Data Exploration: Analyzing the dataset to understand its structure and relationships between variables.
- Data Preprocessing: Handling duplicates and scaling features.
- K-Nearest Neighbors (KNN) Model: Implementing a KNN classifier.
- Model Evaluation: Assessing the model's performance using accuracy and classification report.
- Grid Search for Hyperparameter Tuning: Using grid search to find the best configuration for the model.
- Visualizing Results: Plotting the results, such as accuracy vs. the number of neighbors.

## Instructions

1. Ensure you have the required libraries installed by running: `pip install pandas numpy scikit-learn matplotlib seaborn`.

2. Download the 'glass.csv' dataset or use your own.

3. Run the code provided in the respective sections of the project structure.

4. Explore the README file to understand the process, visualizations, and results.

5. Use the code as a starting point for glass classification projects.

## Results

The KNN model achieved an accuracy of approximately 65.63% on the test data. The best accuracy was 66.67% with two nearest neighbors. You can find more details in the classification report.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please open an issue or a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Have fun exploring glass classification with K-Nearest Neighbors!
