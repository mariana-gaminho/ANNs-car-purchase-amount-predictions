# Car Purchase Amount Prediction

🚗💰 A small machine learning project to predict the total dollar amount that customers are willing to pay for a car.

## Description

This project aims to develop a regression model using artificial neural networks to predict the car purchase amount based on several customer attributes. By leveraging the power of machine learning, we can provide valuable insights into the factors that influence customers' purchasing decisions and estimate the amount they are willing to spend on a car.

The following attributes are used as inputs for our model:

- Gender
- Age
- Annual Salary
- Credit Card Debt
- Net Worth

The trained model will take these attributes as input and provide a prediction for the total dollar amount customers are willing to pay for a car. In real life context, this kind of information could be valuable for car dealerships, financial institutions, and other relevant stakeholders in the automotive industry.

## Usage

To run this project locally, you have two options depending on your preference: using Jupyter Notebook or creating a Conda environment.

### Option 1: Using a Conda Environment (recommended)

1. Clone the repository:
```bash
git clone https://github.com/mariana-gaminho/car-purchase-amount-prediction.git
```

2. Move to the cloned directory:
```bash
cd car-purchase-amount-prediction
```

3. Create the Conda environment using the provided `environment.yml`` file:
```bash
conda env create -f environment.yml
```

4. Activate the Conda environment:
```bash
conda activate car-purchase-prediction-env
```

5. Launch Jupyter Notebook:
```bash
jupyter notebook
```

6. Open the Jupyter Notebook file:
- Navigate to the project directory.
- Open the `car_purchase_prediction.ipynb` file.

7. Run the Jupyter Notebook:
- Execute each cell in the notebook sequentially.
- Make sure to update the data file path in the notebook to match your dataset's location.

8. Explore and experiment:
- Analyze the code, data, and visualizations provided.
- Modify and adapt the notebook to suit your needs.
- Feel free to add new cells for further exploration.

If you choose to use the Conda environment, the `environment.yml` file ensures that you have the required dependencies installed within the environment. This helps create a consistent and reproducible environment for running the project.

### Option 2: Using Jupyter Notebook

1. Clone the repository:
```bash
git clone https://github.com/mariana-gaminho/car-purchase-amount-prediction.git
```

2. Move to the cloned directory:
```bash
cd car-purchase-amount-prediction
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook
```bash
jupyter notebook
```

4. Follow the same steps starting from step 6 in Option 1.

Please note that you will need to have Jupyter Notebook installed on your machine to run the project locally. If you don't have it installed, you can follow the installation instructions provided on the [Jupyter Notebook website](https://jupyter.org/install.html).

By following either of these options, you can explore the code, visualize the data, and experiment with different aspects of the car purchase amount prediction project.

Feel free to reach out if you have any questions or need further assistance! :raising_hand_woman: