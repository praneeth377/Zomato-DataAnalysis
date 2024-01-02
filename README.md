# Zomato Data Analysis

## Introduction
As part of my postgraduate mini-unguided project, I undertook a substantial endeavor involving the preprocessing and analysis of an extensive Zomato dataset. The primary objective was to gain insights into the myriad factors influencing the establishment of diverse restaurants across different locations in Bengaluru. Given Bengaluru's status as the IT capital of India, where a considerable population relies on restaurants for their culinary needs, the competition among eateries is fierce. With an abundance of dining options in the city, the challenge is to distinguish oneself to gain a competitive edge in the business. Assuming the role of a data analyst for a new restaurant, my responsibility is to extract valuable insights from the vast dataset at my disposal, contributing to informed decision-making for the restaurant's success.
   
## Data Description
The provided dataset encompasses fundamental information such as the restaurant's name, address, phone number, website URL, and pertinent details, including ratings on a scale of 5, approximate cost for two people, restaurant type, and the cuisines offered. Additionally, binary indicators convey whether the restaurant provides services like table booking or online orders. This comprehensive dataset equips us with the essential elements for a detailed analysis of the restaurant landscape in Bengaluru.

## Data Pre-Processing
During the data pre-processing phase, meticulous efforts were dedicated to rectifying numerous mistakes, inconsistencies, and duplicate records within the dataset. A thorough examination of each column was conducted to ensure data integrity, involving the scrutiny of data types, identification of null values, and the implementation of relevant imputation strategies where necessary. Extraneous features were systematically dropped to streamline the dataset, while specific columns underwent refinement through the adept utilization of Pandas and string manipulation functions.

Leveraging the capabilities of the ydata_profiling library, an insightful HTML file has been provided, encapsulating the refined dataset's characteristics and structure. Feel free to review the attached HTML file for a detailed overview of the cleaned dataset.

## Data Analysis
Following the cleaning phase, I delved into answering fundamental questions, such as the prevalence of online order acceptance, dominance of specific restaurant chains in Bengaluru, and the popularity of different cuisines. Exploring more intricate relationships, a notable revelation emerged from a scatter plot correlating the approximate cost for two people and the restaurant's rating, with online order status as a distinguishing factor. The plot unveiled that high-end, luxurious establishments offering extravagant cuisines tended to have higher costs but refrained from accepting online orders. This strategic insight suggests a potential avenue for my restaurant to stand out—by embracing online orders for premium culinary offerings. Additionally, contrary to popular belief, the analysis showcased that the most favored cuisines in the city were North Indian, followed closely by Chinese. Armed with these surprising findings, I can guide my restaurant's strategy to prioritize North Indian cuisine over South Indian for optimal business outcomes. The analysis phase has uncovered numerous insightful observations that can shape strategic decisions for my restaurant.

## Future Work and Conclusions
Moving forward, there are exciting opportunities for leveraging machine learning algorithms to predict success metrics, such as restaurant ratings based on features like "approx_cost for 2 people." This predictive modeling can provide valuable insights into factors influencing success and aid in strategic decision-making.

The journey of analysis and exploration is ongoing, and there is always more to uncover from the dataset. Whether it's delving deeper into feature interactions, exploring additional predictive models, or refining existing ones, the possibilities are vast. Continuous exploration can lead to a richer understanding of the data and its implications for your domain.

This project has not only resulted in valuable predictions but has also served as a learning experience. Manipulating datasets and extracting insights using advanced Pandas functions and creating informative visualizations with seaborn plots have expanded my skill set. These newfound techniques and insights will undoubtedly prove beneficial in future fieldwork, allowing to approach data challenges with a more nuanced and informed perspective.

## How to run the codes

To run the provided codes, follow these steps:
* Open the Jupyter Notebook file named 'Zomato_EDA.ipynb.'
* Load the 'Zomato.CSV' dataset into the notebook.
* Execute the cells in the notebook sequentially. This process will perform exploratory data analysis and generate a cleaned dataset named 'Zomato_Cleaned.xlsx.'

* After generating the cleaned dataset, open the 'Zomato_Analysis.ipynb' notebook.
* Load the 'Zomato_Cleaned.xlsx' dataset into the notebook.
* Execute the cells in the notebook sequentially to perform analysis and explore insights. All the questions and relevant insights are provided in notebook itself, feel free to go through them.
