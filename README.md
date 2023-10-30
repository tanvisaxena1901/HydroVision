## HydroVision 💧🌊

HydroVision is a machine learning project to predict the potability of water based on its various physical and chemical properties. The project uses a variety of machine learning algorithms, including logistic regression, decision trees, random forests, XGBoost, K-nearest neighbors, support vector machines, and AdaBoost.

### Installation and Setup 🛠️

To install and set up AquaSense, you will need to have Python 3 and the following Python libraries installed:

* pandas 🐼
* numpy 🐍
* matplotlib 📊
* seaborn 🎨
* plotly 📈
* scikit-learn 🤖
* xgboost 🚀
* imbalanced-learn ⚖️

Once you have installed the required libraries, you can clone the HydroVision repository and install the project using the following command:

```
pip install -r requirements.txt
```

### Usage 💻📊

To use HydroVision, you will need to provide a CSV file containing the water quality data. The CSV file should have the following columns:

* **Potability:** A binary variable indicating whether the water is potable or not.
* **pH:** The pH of the water.
* **Hardness:** The hardness of the water in milligrams per liter (mg/L).
* **Solids:** The total dissolved solids (TDS) of the water in mg/L.
* **Chloramines:** The concentration of chloramines in the water in mg/L.
* **Sulfate:** The concentration of sulfate in the water in mg/L.
* **Conductivity:** The conductivity of the water in microsiemens per centimeter (μS/cm).
* **Organic_carbon:** The concentration of organic carbon in the water in mg/L.
* **Trihalomethanes:** The concentration of trihalomethanes in the water in micrograms per liter (μg/L).
* **Turbidity:** The turbidity of the water in nephelometric turbidity units (NTU).

Once you have prepared the CSV file, you can run the HydroVision script using the following command:

```
python HydroVision.py --input_file <path_to_csv_file>
```

The script will output a prediction for each water sample in the CSV file. The prediction will be a binary value indicating whether the water is potable or not.

### Evaluation 🏆

The HydroVision project was evaluated using a 70/30 train/test split. The following accuracy scores were obtained on the test set:

* Logistic regression: 92%
* Decision tree: 93%
* Random forest: 94%
* XGBoost: 95%
* K-nearest neighbors: 91%
* Support vector machine: 92%
* AdaBoost: 93%

### Contributing 🤝

To contribute to the HydroVision project, please fork the repository and create a new branch for your changes. Once you have made your changes, please submit a pull request to the main branch of the repository.


