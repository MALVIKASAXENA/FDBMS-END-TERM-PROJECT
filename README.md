# FDBMS-END-TERM-PROJECT
This is the dataset from kaggle Reddit_Data Amber Heard - Social Network Analysis. Only the data of 2018 is taken from the Reddit. Tools which are used are Google Colab, Python and Gephi.
# Our-Network-Layout
![image](https://user-images.githubusercontent.com/93215848/163786895-8d1ec650-c04f-408a-afd0-d6a23f9ecb72.png)
![image](https://user-images.githubusercontent.com/93215848/163787000-512172de-e4ca-4aa7-bb72-cf42764d45c7.png)
# Coloured nodes as per community class
![image](https://user-images.githubusercontent.com/93215848/163787197-52d772c7-7a0f-417f-aa08-d51c03e3b1fd.png)
# The Pink one denotes Sreddit id ( Subreddit id) and Green ones denotes pid ( Parent id)
![image](https://user-images.githubusercontent.com/93215848/163787283-0753b7cf-6fb9-4765-a028-f903df0bfff3.png)
# Edge weight filter which displays strong bindings
![image](https://user-images.githubusercontent.com/93215848/163787437-a15329e3-6a0f-4a9a-bccf-15efdbfec101.png)
# Conclusion
In our data we have about 4.71% is subreddit which means that 4.71% data is a specific to some community/post whereas the rest 95.29% data is normal texts and has a parent id. From our modularity test we got to know we have 133 communities which is a high number which means we have dense connections between the nodes within modules but sparse connections between nodes in different modules. Through our modularity class we got to know that 6-7 communities dominate with 13.22% coming from community 5 (Pink) and 13.03% coming from community 58 (Green). After that from nested filters we got to know sentiment of each text whether it was positive/negative/neutral and grouped them accordingly. According to our data p31 is of a  positive sentiment , eg “First thing that pops into my head. Every time". We also got to know that 13.85% text were negative , 25.02% positive and rest were neutral . Then we say Edge weigh filter which is highest with p2573 (Source) and P2601(Target) which is 1160 (shows the strongest connection).
