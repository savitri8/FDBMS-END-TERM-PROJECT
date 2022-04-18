# FDBMS-END-TERM-PROJECT
Social Network Analysis
This is the dataset from kaggle Reddit_Data Amber Heard - Social Network Analysis. Only the data of 2018 is taken from the Reddit. Tools which are used are Google Colab, Python and Gephi.
# Our-Network-Layout
![image](https://user-images.githubusercontent.com/93476079/163828565-24afbd49-a234-4f66-840d-43db7576c081.png)
![image](https://user-images.githubusercontent.com/93476079/163828636-d6eb06d8-8aac-4990-9dd6-fb9d9ccf4275.png)
# Coloured nodes as per community class
![image](https://user-images.githubusercontent.com/93476079/163828689-074b6ffe-8c5f-4fc5-b258-c41de2273134.png)
# The Pink one denotes Sreddit id ( Subreddit id) and Green ones denotes pid ( Parent id)
![image](https://user-images.githubusercontent.com/93476079/163828729-06b6f4ba-2ffb-4daf-87d2-6a06ed89118c.png)
# Edge weight filter which displays strong bindings
![image](https://user-images.githubusercontent.com/93476079/163828792-48417cbb-df3a-412f-b106-c4af49d9d9df.png)
# Conclusion
In our data we have about 4.71% is subreddit which means that 4.71% data is a specific to some community/post whereas the rest 95.29% data is normal texts and has a parent id. From our modularity test we got to know we have 133 communities which is a high number which means we have dense connections between the nodes within modules but sparse connections between nodes in different modules. Through our modularity class we got to know that 6-7 communities dominate with 13.22% coming from community 5 (Pink) and 13.03% coming from community 58 (Green). After that from nested filters we got to know sentiment of each text whether it was positive/negative/neutral and grouped them accordingly. According to our data p31 is of a positive sentiment , eg “First thing that pops into my head. Every time". We also got to know that 13.85% text were negative , 25.02% positive and rest were neutral . Then we say Edge weigh filter which is highest with p2573 (Source) and P2601(Target) which is 1160 (shows the strongest connection).

