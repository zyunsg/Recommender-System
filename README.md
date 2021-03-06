# Recommender-System(RecSys)
### Overview:
RecSys: to recommend the *appropriate* items to the *potential* users who are likely to buy, subscribe, listen, watch...<br/>

### Approaches: 
1. Content-based: A content-based system is to recommend items that are similar to those that a user liked in the past, and it is based on item description and a profile of the users' preferences.<br/>
2. Collaborative filtering(CF): Predicting users' preference based on their similarity to others by analyzing their behaviors, past activities or preferences. Note that it does not analyze item content.
   * Two forms of data:
       - explicit feedback
       - implicit feedback
   * Two primary areas:
       - neighborhood methods
       - latent factor models
   * Three Challenges in CF
       - Cold start: new users and/or items
       - Scalability: future item expansion
       - Sparsity: low user-item interaction. Users only hold a few out of tons of items.<br/>
3. Hybrid RecSys: Combine Content-based and CF and can be implemented in several ways.

### Classical example: Netflix 
This is a good reference and tutorial to understand [matrix factorization](https://endymecy.gitbooks.io/spark-ml-source-analysis/content/%E6%8E%A8%E8%8D%90/papers/Matrix%20Factorization%20Techniques%20for%20Recommender%20Systems.pdf) for RecSys applications. 

### Packages:
+ [lightfm](http://lyst.github.io/lightfm/docs/home.html)
### Reference:<br/>
[wiki-Recommender System](https://en.wikipedia.org/wiki/Recommender_system)<br/>
[Stanford-Recsys Chapter 9](http://infolab.stanford.edu/~ullman/mmds/ch9.pdf)<br/>
[Matrix Factorization Techniques For RecSys](https://endymecy.gitbooks.io/spark-ml-source-analysis/content/%E6%8E%A8%E8%8D%90/papers/Matrix%20Factorization%20Techniques%20for%20Recommender%20Systems.pdf)


