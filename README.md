# Mall Customer Segmentation using K-Means Clustering

## Project Overview
This project applies K-Means clustering to segment customers based on their shopping behaviors using the Mall Customer Segmentation dataset. The primary goal is to group customers into distinct clusters for targeted marketing strategies and better customer understanding.

## Dataset
The dataset used is the **Mall Customer Segmentation Data**, which contains the following features:
- `CustomerID`: Unique identifier for each customer.
- `Gender`: Gender of the customer.
- `Age`: Age of the customer.
- `Annual Income (k$)`: Annual income of the customer in thousand dollars.
- `Spending Score (1-100)`: A score assigned to the customer based on their spending behavior and purchasing history.

## Project Structure
```
Mall-Customer-Segmentation/
├── data/
│   └── Mall_Customers.csv
├── src/
│   └── kmeans_clustering.py
├── README.md
└── requirements.txt
```
- `data/`: Contains the dataset.
- `src/`: Contains the Python script for K-Means clustering.
- `README.md`: Project documentation.
- `requirements.txt`: List of dependencies.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Mall-Customer-Segmentation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Mall-Customer-Segmentation
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Place the `Mall_Customers.csv` dataset in the `data/` directory.
2. Run the K-Means clustering script:
   ```bash
   python src/kmeans_clustering.py
   ```
3. The script will output the cluster labels and visualize the clusters based on `Annual Income` and `Spending Score`.

## Results
- The script uses the Elbow Method to determine the optimal number of clusters.
- The clustered data is visualized, showing customer segments based on their annual income and spending scores.

## Visualizations
The project includes visualizations such as:
- **Elbow Method Plot**: Helps to identify the optimal number of clusters.
- **Cluster Scatter Plot**: Visualizes the clusters using features like `Annual Income` and `Spending Score`.

## Dependencies
- Python 3.7+
- pandas
- numpy
- matplotlib
- scikit-learn

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
- Dataset source: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

## Contact
For any questions or suggestions, please contact [your email or GitHub profile link].

    
