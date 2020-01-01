# Article-Recommender-System
Comparing (and attempting to improve) the effectiveness of a popularity model, content-based filtering model, collaborative filtering model and hybrid model for an article recommender system.

ACKNOWLEDGEMENTS

This project was made through following this very helpful tutorial with slight alterations: https://www.kaggle.com/gspmoreira/recommender-systems-in-python-101

Through my alterations, I somehow managed to make the all the recommenders less effective by a magnitude of 10. I'm sensing there is a bug in my evaluator class. Do let me know if you can find it as increasing the effectiveness of my models by a factor of 10 would make them more effective than the models in the tutorial 🙃.

A strong understanding of how cosine similarity and matrix factorization are applied to recommender systems was gained from this awesome article: https://realpython.com/build-recommendation-engine-collaborative-filtering/

MOTIVATION & GOALS

My main motivator was to understand how recommender systems, like those of Netflix and Amazon, work. Aside from gaining a strong foundation of the math behind it, I consider this project a great resource that I can pull from in future projects as I have skeletons of the 4 most common types of recommender systems.

Though this was a follow-along project with a tutorial, I ensured I made alterations to see if my heuristics could improve the models. Currently, it seems they did not, but I sense I did something buggy.

NEW TOOLS AND EXCITING EXPERIENCES!

I used the nltk library for the first time, particularly the 'stopwords' attribute. That was fun. I also 'vectorized' article text. That was really cool. Hopefully I can explore more natural language processing in the near future.

Though I made classes in C++ before for my SYDE121 course, I never made them in python, so it was good to see the syntax wasn't far from what I expected it to be.

CONCLUSION

In the end, though my evaluator was wonky, when I tested the hybrid model on an actual user profile it spat out sensical recommendations that matched their preferences! That made it all worth it for me, and the power of these simple algorithms really amazed me. It felt like magic 🤯.

FUTURE?

In the future, I would love to apply this to another dataset to continue my work on a restaurant recommender. Also, it would be a good idea to split the articles by time when making the test and train datasets to better imitate what the process would be like in 'real-life'. I would love to explore matrix factorization in greater depth and learn more advanced techniques in RecSys.
