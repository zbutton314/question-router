# question-router
**Team Beta**: Zach Button & Adam Flowerday

File Location: https://drive.google.com/drive/u/0/folders/1JwGMvRrlptyIfmMSezMPYXGPubGuwG-4
- **Questions.csv**: StackOverflow questions (title + body)
- **Tags.csv**: StackOverflow question tags
- **Answers.csv**: StackOverflow answers (not used for this project)
- **matrix_title.pkl**: Serialized CountVectorizer transformer for title (Top 2,000 terms)
- **matrix_body.pkl**: Serialized CountVectorizer transformer for body (Top 2,000 terms)
- **tfidf.pkl**: Serialized TF-IDF transformer for all token counts (4,000 total)
- **model**: Serialized Keras model
- **data.csv**: Preprocessed data, ready for model build
- **experts.csv**: Example Expert database with 20 experts and no questions assigned
