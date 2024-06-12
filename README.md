# Evaporation Rate Prediction

## Overview
This repository contains various Jupyter notebooks for implementing and evaluating different machine learning models for predicting evaporation rates. The models include Multi-Layer Perceptron (MLP) models, and the notebooks explore using different subsets of attributes.

## Repository Structure
- `MLP ER-10.ipynb`: MLP model for evaporation rate prediction using the top 10 attributes.
- `MLP ER-5.ipynb`: MLP model for evaporation rate prediction using the top 5 attributes.
- `MLP ER-All.ipynb`: MLP model for evaporation rate prediction using all available attributes.
- `MLP ER.ipynb`: MLP model for evaporation rate prediction with a custom set of attributes.
- `MLP TC.ipynb`: MLP model for temperature correction.

## Getting Started

### Prerequisites
Ensure you have the following libraries installed:
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

You can install them using pip:
```bash
pip install tensorflow keras numpy pandas scikit-learn matplotlib
```

### Running the Notebooks
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/bluecodeindia/Evaporation-Rate.git
    cd Evaporation-Rate
    ```

2. **Open the Notebooks**:
    Use Jupyter Notebook or JupyterLab to open the notebooks. For example:
    ```bash
    jupyter notebook MLP\ ER-10.ipynb
    ```

3. **Run the Cells**:
    Execute the cells in each notebook sequentially to train and evaluate the models.

## Notebooks

### Evaporation Rate Prediction
- `MLP ER-10.ipynb`: This notebook implements an MLP model for predicting the evaporation rate using the top 10 attributes.
- `MLP ER-5.ipynb`: This notebook implements an MLP model for predicting the evaporation rate using the top 5 attributes.
- `MLP ER-All.ipynb`: This notebook implements an MLP model for predicting the evaporation rate using all available attributes.
- `MLP ER.ipynb`: This notebook implements an MLP model for predicting the evaporation rate with a custom set of attributes.

### Temperature Correction
- `MLP TC.ipynb`: This notebook implements an MLP model for temperature correction.

## Contributing
Feel free to contribute by submitting a pull request. Please ensure your changes are well-documented and tested.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or inquiries, please contact [bluecodeindia@gmail.com](mailto:bluecodeindia@gmail.com).
