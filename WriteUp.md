# AWS ML Training - NLP - Topic Modeling

## Goals
As a product owner, I would like to understand why cusomters have left negative reviews on Amazon.

## Dataset
As part of the project, we will be using the following dataset:
- [Amazon reviews classified as positive and negative](s3://nlp-workshop-reviews/amazon_review_polarity_csv.tgz)
- [NLTK list of English stopwords](https://gist.github.com/sebleier/554280)

## Strategy
1. Identify subset of negative reviews
2. Apply NLP (e.g. lemmatization, stopwords removal, etc.)
3. Execute Neural Topic Model to extract topics from reviews

## References
- [AWS Documentation on Neural Topic Model (NTM) Algorithm](https://docs.aws.amazon.com/sagemaker/latest/dg/ntm.html)
- [Topic Modeling Amazon Product Reviews](https://kldavenport.com/topic-modeling-amazon-reviews/)
