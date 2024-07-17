Football Skills Analysis and Clustering
This project explores the skills of football players and clusters them based on their attributes using the FIFA 20 dataset. The analysis aims to identify distinct player profiles based on key skills such as shooting, passing, dribbling, and defending.

Dataset
The dataset used for this analysis is "players_20.csv" from the FIFA 20 Career Mode. It includes detailed attributes for each player, such as:

Overall rating
Value
Potential
Individual skill attributes (e.g., shooting, passing, dribbling, defending)
Player positions
Nationality
Club
Analysis
Objectives
Data Cleaning: Handle missing values and convert relevant columns to appropriate data types.
Exploratory Data Analysis (EDA): Gain insights into player attributes and distributions.
Clustering: Group players into clusters based on their skill attributes.
Methodology
Data Cleaning:

Handled missing values for relevant columns.
Converted columns like player skill attributes to numeric values.
EDA:

Visualized the distribution of player ages using a bar chart.
Analyzed the top nationalities and clubs represented in the dataset.
Explored the distribution of player heights using a histogram.
Clustering:

Selected key skill attributes: shooting, passing, dribbling, and defending.
Standardized the data for clustering.
Applied the K-means clustering algorithm to group players into clusters.
Results
The K-means clustering resulted in four distinct clusters with the following average attributes:

Cluster	Shooting	Passing	Dribbling	Defending
0.	65.92	69.48	73.19	54.62
1.	31.62	43.43	46.55	60.76
2.	59.73	53.69	63.96	30.46
3.	46.69	58.51	61.89	62.55
Conclusion
The clustering analysis identified four distinct player profiles based on their skill attributes:

Cluster 0: Players with strong shooting, passing, and dribbling skills but moderate defending.
Cluster 1: Defensive players with lower shooting, passing, and dribbling skills.
Cluster 2: Players with balanced shooting and dribbling skills but weaker defending.
Cluster 3: Players with balanced skills across all attributes, excelling slightly more in defending.
These profiles help in understanding the distribution of skills among players and can assist in strategic team formation and player selection.

Visualizations
Age Distribution: A bar chart showing the distribution of player ages.
Nationality Distribution: A bar chart displaying the number of players from the top 10 nationalities.
Player Height Distribution: A histogram representing the distribution of player heights.
Clustering Results: A bar chart showing the average attributes for each cluster.
Repository Structure
kotlin
Copy code
.
├── data
│   └── players_20.csv
├── notebooks
│   └── football_analysis.ipynb
├── images
│   └── age_distribution.png
│   └── nationality_distribution.png
│   └── height_distribution.png
│   └── clustering_results.png
└── README.md
How to Run
Clone the repository.
Ensure you have the required libraries installed: pandas, numpy, matplotlib, seaborn, sklearn.
Open the Jupyter notebook football_analysis.ipynb and run the cells sequentially.
Contact
For any questions or feedback, feel free to contact me at ratheeshkrishnan.rk7@gmail.com.
