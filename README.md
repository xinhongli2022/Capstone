## Parents and Teachers

## Problem Statement
When we talk about education for children, there are two groups of people play very important roles, parents and teachers. When the world is changing, roles and expectations of them  might be different than before. Especially we experienced covid 19, parents and teachers’ emotion  might face challenge. As a data scientist at BetterFuture company, I would explore their concerns and interests through social media, provide suggestions to company’s goal.

The reason I am particularly interested in emotions because I heard ome people say that in the past, when a child failed tests or did something bad, parents would yelled at their child, but now, some parents might turn to teachers, yelling the same sentence, What is wrong with you.



## Link to notebooks, table of contents
1. **Data cleanup**
- Parenting Data: [Link](https://github.com/xinhongli2022/Capstone/blob/main/notebook/Parenting_Data_collecting.ipynb)
- Teachers Data: [Link](https://github.com/xinhongli2022/Capstone/blob/main/notebook/Parenting_Data_collecting.ipynb)
- Data Cleaning: [Link](https://github.com/xinhongli2022/Capstone/blob/main/notebook/Data_cleaning.ipynb)
2. **Content Analysis**
- Parenting : [Link](https://github.com/xinhongli2022/Capstone/blob/main/notebook/Parenting_Text_Analysis.ipynb)
- Teachers : [Link](hhttps://github.com/xinhongli2022/Capstone/blob/main/notebook/Teaher_Text_Analysis.ipynb)
- Sentiment/emothin analysis: [Link](https://github.com/xinhongli2022/Capstone/blob/main/notebook/sentiment_analysis.ipynb)
- More sentiment analyis on parent: [Link](https://github.com/xinhongli2022/Capstone/blob/main/notebook/vader_parents.ipynb)
- More sentiment analyis on Teacher: [Link](https://github.com/xinhongli2022/Capstone/blob/main/notebook/vader_teacher.ipynb)
3. **Modeling**
- Modeling: [Link](https://github.com/xinhongli2022/Capstone/blob/main/notebook/Modeling.ipynb)



## Models
- CountVectorizer and LogisticRegression     0.959    0.903
- CountVectorizer and RandomForestClassifie  0.996    0.896
- TfidfVectorizer and  LogisticRegression    0.963    0.910
- TfidfVectorizer and RandomForestClassifier 0,996    0,890
- CountVectorizer and MultinomialNB          0.925    0.896
- TfidfVectorizer and MultinomialNB          0.938    0.902
- CountVectorizer and Keras                  0.993    0.894

### TfidfVectorizer and  LogisticRegression will be chosen as good model to work on future APP


## Conclusion and future work
1. Parents and teachers are doing OK, they do have different concerns, need different support. 
2. Implement an APP to provide appropriate support based on user’s input
3. Compare the data with data from 3 years ago, to see the impact of Covid 19
4. Would love to conduct a similar analysis on different language in different countries to see if there are culture difference, and explore language translation




