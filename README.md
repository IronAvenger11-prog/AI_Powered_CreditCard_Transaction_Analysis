# AI-powered Customer Segmentation and Market Analysis



Welcome to the Intelligent Bank Marketing Program! This project, completed alongside Coursera, focuses on creating an advanced marketing strategy based on customer classification and segmentation using unsupervised learning techniques. By leveraging the power of AI, specifically the K-means clustering algorithm, we are able to segment customers into distinct categories. Furthermore, we employ the elbow method for optimizing the number of clusters and utilize Principal Component Analysis (PCA) to analyze the newly created principal components. 

## Customer Segmentation Results

After the segmentation process, we identified four main customer clusters:

1. **Transactors:** This cluster represents customers who exhibit cautious financial behavior, maintaining the lowest balances ($104) and cash advances ($303). They tend to make partial payments, with a percentage of full payment at 23%.

2. **Revolvers:** The second cluster consists of customers who use their credit cards as a loan, making it the most lucrative sector. They have the highest balances ($5000) and cash advances (~$5000), but display low purchase frequency. This group has a high cash advance frequency (0.5), a significant number of cash advance transactions (16), and a low percentage of full payment (3%).

3. **VIP/Prime:** The third cluster represents VIP or Prime customers who have high credit limits of $16,000 and exhibit the highest percentage of full payment. They are an ideal target for increasing their credit limits and encouraging higher spending habits.

4. **Low Tenure:** The fourth cluster comprises customers with low tenure (7 years) and low balances. They require special attention due to their lower engagement with the bank's services.

## Analysis and Insights

To gain a comprehensive understanding of each customer group, we generated various types of graphs and visualizations. These plots provide valuable insights into the behavior and preferences of each cluster, allowing for targeted marketing strategies and personalized customer experiences.


![image](https://github.com/IronAvenger11-prog/Intelligent-bank-marketing-program/assets/85229612/296cc231-c5ce-466d-a2b6-b170815b6224)
![image](https://github.com/IronAvenger11-prog/Intelligent-bank-marketing-program/assets/85229612/c69c5352-ee6a-444c-8a57-23984e944a8d)


## Prerequisites

To run this project locally or reproduce the results, ensure that you have the following dependencies installed:

- Python 3
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

## Usage

1. Clone this repository:

```bash
git clone [https://github.com/IronAvenger11-prog/](https://github.com/IronAvenger11-prog/Intelligent-bank-marketing-program)
```

2. Navigate to the project directory:

```bash
cd Intelligent-bank-marketing-program
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Execute the cells in the notebook to observe the customer segmentation and analysis.

For detailed walkthrough, check the code : (https://github.com/IronAvenger11-prog/AI_Powered_CreditCard_Transaction_Analysis/blob/main/Marketing_Department_Solution.ipynb)


## Acknowledgments

We would like to express our gratitude to Coursera and the project instructors for providing valuable guidance and resources throughout this project.

## References

- [K-means Clustering Algorithm](https://en.wikipedia.org/wiki/K-means_clustering)
- [Principal Component Analysis (PCA)](https://en.wikipedia.org/wiki/Principal_component_analysis)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
