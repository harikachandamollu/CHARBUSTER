# CHARBUSTER
CHARBUSTER : CONTENT-BASED HYBRID APPROACH FOR RECOMMENDING BOOKS ON USERSCOPE, TYPE, EXPERIENCE AND READING-BEHAVIOUR

Book recommendation system recommends books to users based on their past interactions, choices, and behaviour. Techniques to recommend books include collaborative filtering, content based, context aware, social and demographic. These techniques face several limitations, causing them to fail in providing accurate and effective recommendations. One such main research problem in book recommendation setting is data sparsity. Most algorithms only include metadata of the books because often full text is not available, or it cannot be used due to reasons like copyright infringement. Additionally, it is difficult to exploit the full content of the book. Depending entirely on either user data, metadata, or content of the book might not be an ideal way to have effective recommendations. All the feature sets such as writing style of the author, genre of the book, rating and review of the book from other users have an impact on the recommendation setting. Moreover, there are different types of readers or user types who read books on different motives. One single measure or feature set might not be successful in recommending books to all types of readers. Considering this key point of treating users differently might help to get better recommendations. The idea is to develop a model with a hybrid approach (user based and text/content based) which includes user types, interactions, and content of the book. Besides, observing how availability of information influencing the performance of the model, helps to decide which features are necessary for good recommendations. Through this, we could measure whether the proposed model achieves similar performance even with less information compared to baseline techniques such as collaborative and content-based techniques using tf-idf approach. 

# Research Questions
- Which feature sets are relevant for different user types in a book recommendation setting?
- How do the features influence the recommendation, and when should different user types be considered?
- How does the model behaviour change with the amount of information provided, and what is the minimum
amount needed to provide ‘good’ recommendations?

# Subtasks
- Analysis of book related features (writing style, genre, review and so on) and extract user types based on the
features and identify the correlation to the literature.
- Build a hybrid approach and analyse the performance of the model for different feature sets depending on user
type.
- Evaluate how user types influence the recommendations and what features influence them most.
- Compare the model with baselines (collaborative and content-based models with tf-idf approach).
- Analysing the behaviour and the performance of the model with the change in amount of information (abstract/
first pages/ full text) provided.
