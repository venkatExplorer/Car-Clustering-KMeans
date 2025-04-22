Car Feature Clustering with K-Means
This project uses K-Means Clustering to group cars based on their features like miles per gallon (mpg), displacement (disp), and horsepower (hp). The idea is to find natural groupings among vehicles and understand patterns in the data.

 What This Project Does
Loads a dataset of cars from a CSV file.

Extracts the features: mpg, disp, and hp.

Applies K-Means Clustering:

First with 3 clusters

Then with 5 clusters

Groups and prints the cars belonging to each cluster for both versions.

This helps in visualizing how cars can be grouped based on performance-related features.

 Dataset
The project uses a CSV file named cars-1.csv. It should be placed in the same directory or updated in the code path.

Required Columns:
mpg: Miles per gallon

disp: Engine displacement

hp: Horsepower

Make sure these columns are present in the dataset for the code to work correctly.

 How to Run
Make sure you have Python installed (Python 3.6+ recommended).

Install the required library if not already installed:

pip install pandas scikit-learn

Run the script:

python KMeans.py

You'll see the output of both 3-cluster and 5-cluster groups printed in the console.

What is K-Means?
K-Means is an unsupervised learning algorithm used to group data into K number of clusters based on similarity. It tries to find patterns in data where no labels are available.

Example Use Cases
Classifying vehicles based on performance.

Understanding car segments without predefined categories.

Feature grouping for market analysis.

Author
Venkat Boda – A data enthusiast exploring clustering in car data.

 License
This project is open for learning and experimenting. Use it however you'd like!

