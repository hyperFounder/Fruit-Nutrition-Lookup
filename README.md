# Fruit Nutrition Analysis

This Jupyter Notebook project provides a comprehensive analysis of fruit nutrition data, enabling users to explore and visualize nutritional information, understand relationships between nutritional attributes, and perform Hierarchical Clustering analysis. The project offers the following key features:

- **Display Nutrition Information:** Given a fruit name, the program provides detailed nutritional information, including calories, fat, sugar, carbohydrates, and protein.

- **Graphical Relationships:** Visualize relationships between nutritional attributes through scatter plots with linear regression lines. This allows users to understand correlations between attributes such as calories, sugar, fat, carbohydrates, and protein.

- **Hierarchical Clustering:** Utilize the SLINK hierarchical clustering algorithm to group fruits based on their nutritional similarities. The project calculates the Cophenetic Correlation Coefficient (CPCC) to evaluate the quality of the clustering.

# Features

## Retrieve Nutritional Information

Users can simply input the name of a fruit, and the program will access and present detailed nutritional information:

- Calories (kcal)
- Fat (grams)
- Sugar (grams)
- Carbohydrates (grams)
- Protein (grams)
  
## Data Source: FruityVice API 🍎🍌

Okay, so, where do we get all that cool fruit nutrition data? We're buddies with the [FruityVice API!](https://www.fruityvice.com/#1) 🤝
- This project relies on the FruityVice API to dish out the latest and greatest info on all your favorite fruits. It's like our secret weapon for nutrition facts.
- No more guessing about how healthy your snacks are – we've got the inside scoop, thanks to our fruity friend at FruityVice! 🍓
 
## Visualize Nutritional Relationships
The program offers a range of options for visualizing relationships between nutritional attributes. Users can explore correlations such as:

- **Linear Regression:** A vstatistical method used to model the relationship between two or more variables. In the context of this project, linear regression is applied to nutritional attributes. Each scatter plot is accompanied by a linear regression line, which represents the "best-fit" straight line through the data points. This line demonstrates the direction and strength of the relationship between two nutritional attributes.

- **Correlation Coefficient (r):** The project calculates the Pearson correlation coefficient (r) for each pair of attributes. This coefficient quantifies the degree of correlation between two variables. A positive r value indicates a positive correlation, while a negative r value indicates a negative correlation. The magnitude of r represents the strength of the relationship, with values closer to 1 or -1 indicating a stronger correlation.

## Explore Hierarchical Clustering
Hierarchical clustering is used to group fruits based on their nutritional profiles. Users can interact with dendrograms and assess clustering quality through the Cophenetic Correlation Coefficient (CPCC).

- **SLINK Algorithm:** The project employs the SLINK (single-linkage) hierarchical clustering algorithm. SLINK determines the similarity between clusters by considering the minimum pairwise distance between their members. This method creates hierarchical clusters that are particularly effective at handling elongated and irregularly shaped clusters in the data.

- **Cophenetic Correlation Coefficient (CPCC):** To assess the quality of the clustering results, the project calculates the Cophenetic Correlation Coefficient (CPCC). The CPCC quantifies how faithfully the hierarchical clustering represents the original data distances. A higher CPCC indicates that the hierarchical structure accurately reflects the similarities between fruits in the dataset.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:
```
git clone https://github.com/your-username/fruit-nutrition-analysis.git
```
2. Install the required Python libraries using pip:
```
!pip install pandas matplotlib scipy scikit-learn
```
3. Run the [Jupyter Project File](https://github.com/hyperFounder/Fruit-Nutrition-Lookup/blob/main/Fruit_Nutrition_Lookup.ipynb) and follow the on-screen menu to explore and analyze fruit nutrition data.

### License
This project is licensed under the [MIT License.](https://github.com/hyperFounder/Fruit-Nutrition-Lookup/blob/main/LICENSE)
