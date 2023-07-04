# Grocery Store Sales Insight using Association Rule and Apriori Algorithm

This report focuses on applying data mining techniques, specifically the Association Rule and Apriori algorithm, to analyze a grocery store dataset. The goal is to gain insights into the sales patterns and relationships among grocery store items. The report begins by explaining the applied algorithms, followed by a discussion of the results.

## Frequent Itemset Generation
Frequent itemset generation is a data mining technique used to identify sets of items that frequently occur together in a dataset. This technique is commonly employed in market basket analysis to discover items that are commonly purchased together in a retail setting.

## Rule Generation
Rule generation involves automatically creating rules from data. These rules can be used for various tasks such as classification, prediction, and decision making. Techniques such as decision tree induction, association rule mining, and Bayesian networks are employed for rule generation. These techniques can handle both structured and unstructured data and generate rules ranging from simple if-then statements to complex relationships.

## One-Hot Encoding
One-hot encoding is a process of converting a categorical variable into a binary vector representation. Each unique value in the categorical variable is transformed into a binary vector, with a 1 in the corresponding position and 0s elsewhere. This technique is useful in machine learning and statistics when dealing with categorical data and neural networks that require input in a specific format.

## Association Rule Generation
Association rule generation is a technique used to discover relationships between items in a dataset. It is commonly utilized in market basket analysis to identify frequently co-occurring items. The Apriori algorithm is one of the most widely used algorithms for association rule generation.

## Apriori Algorithm
The Apriori algorithm identifies items that appear together in transactions with a minimum support threshold. The support threshold measures the frequency of item or item combinations in the dataset. Once the items meeting the support threshold are identified, the algorithm generates rules describing the relationships between those items. The generated rules take the form of if-then statements, ranking them based on measures like confidence or lift.

Association rule generation and the Apriori algorithm find applications in various fields such as retail, marketing, and healthcare. They provide insights into customer behavior, product placement, and stock management.

## Dataset
The chosen dataset consists of grocery store transaction records and includes the following columns:
- Member Number
- Date
- Item Description

It is important to note that if a customer bought multiple products on the same day, it is considered one transaction.

## Analysis and Results
In this report, the association rule and Apriori algorithms are applied to the grocery store dataset to identify frequently used items. With the Apriori algorithm, the analysis reveals that "tropical fruit" is the most frequently purchased item, followed by "whole milk" and "pip fruit." On the other hand, the association rule approach shows that the most significant conviction value occurs between "bottled beer" and "whole milk" as antecedents and consequents. Additionally, the combination of "sausages" and "whole milk" also exhibits a significant conviction value. The results indicate that "whole milk" is commonly purchased alongside items such as bottled beer, newspaper, sausages, and domestic eggs.

In total, 74 rules were generated to illustrate these relationships.

Please refer to the project code and analysis results for a more detailed examination.

If you have any questions or require further clarification, please feel free to reach out.

Thank you for your interest in this project!
