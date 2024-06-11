# **PRODIGY_ML_02** 

## Task-2 of ML Internship at Prodigy Infotech

*Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.*

## Overview

I implemented a K-Means clustering algorithm to segment customers based on their demographics and spending behavior. This task helps in identifying distinct customer groups for targeted marketing strategies.

## Dataset
The dataset used in this project is the Mall Customer Segmentation Data. It contains information about 200 mall customers.

### Features
- CustomerID: Unique ID for each customer
- Gender: Gender of the customer
- Age: Age of the customer
- Annual Income (k$): Annual income of the customer in thousands of dollars
- Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature

## Methodology

### Elbow Method
Used the Elbow Method to determine the optimal number of clusters by plotting the inertia for different values of K.

### K-Means Clustering
Implemented the K-Means algorithm to segment the customers into distinct clusters based on the selected features:
- Annual Income
- Spending Score

### Visualization
Visualized the clusters using scatter plots to interpret the customer segments.

## Repository Contents
- `README.md`: Project documentation.
- `ML Task-2`: Contains all the files of the project 
  - `Mall_Customers.csv`: The dataset used for clustering.
  - `t-2_model.ipynb`: Jupyter notebook containing the complete implementation of the K-Means clustering algorithm, including data preprocessing, clustering, and visualization steps.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/U-Jayadhar/PRODIGY_ML_02.git
    ```
2. Navigate to the repository directory:
    ```sh
    cd PRODIGY_ML_01
    ```
3. Open the Jupyter notebook:
    ```sh
    jupyter notebook t-2_model.ipynb
    ```
4. Run the cells in the notebook to see the implementation and results.

## Results
The clustering results helped in identifying different customer segments, which can be used for:

- Personalized marketing strategies
- Improving customer satisfaction
- Enhancing business decision-making

![Scatter Plot Output](https://github.com/U-Jayadhar/PRODIGY_ML_02/blob/main/K-means%20output.png)

## Acknowledgements
This project is based on the [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data) dataset on Kaggle.

## Contact

For any queries or suggestions, feel free to contact me 

Linkedin: [Jayadhar Ummadingu](https://www.linkedin.com/in/jayadhar-ummadisingu-2a825b25a/)

E-mail: jummadis@gitam.in