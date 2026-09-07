# Data Mining with R

Netflix – “Because You Watched” Using Association Rule Mining
📌 Project Overview

This project demonstrates how Association Rule Mining can be used to create a Netflix-style “Because You Watched” recommendation system.

The system analyzes users' viewing patterns and discovers relationships between movies/TV shows. Based on these relationships, it recommends other content that a user may be interested in.

🎯 Objectives
Analyze Netflix viewing data.
Discover relationships between movies and TV shows.
Apply Association Rule Mining.
Generate personalized recommendations.
Understand how recommendation systems work.
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
MLxtend
Association Rule Mining
Apriori Algorithm
🔍 Methodology
Collect Dataset
Use Netflix viewing-history data containing users and the movies/shows they watched.
Data Preprocessing
Remove missing values.
Organize viewing records.
Convert the data into a transaction format.
Generate Frequent Itemsets
Apply the Apriori Algorithm to identify frequently watched combinations.
Generate Association Rules
Calculate:
Support
Confidence
Lift
Recommendation Generation
If a user watches a particular movie/show, the discovered association rules can be used to recommend related content.
📊 Example
Watched Content	Recommended Content
Stranger Things	Wednesday
Money Heist	Squid Game
The Witcher	Shadow and Bone
Breaking Bad	Better Call Saul
Dark	Black Mirror

For example:

Because you watched “Stranger Things” → You may also like “Wednesday”.

📈 Association Rule Metrics
Support

Shows how frequently an item combination appears in the dataset.

Confidence

Shows how likely users who watched one item are to watch another item.

Lift

Measures how strongly two items are associated compared with random occurrence.

🚀 Future Enhancements
Add real Netflix viewing-history data.
Build a graphical user interface.
Create a web-based recommendation system.
Use collaborative filtering and machine learning.
Combine Association Rule Mining with content-based recommendations.
👨‍💻 Author

Harsh Saraswat

⭐ Conclusion

The Netflix “Because You Watched” Recommendation System shows how Association Rule Mining can identify viewing patterns and generate useful recommendations. This project provides a simple understanding of how data mining techniques can be applied to real-world recommendation systems.
