# Topic-Identification-using-LDA
Identifying topic of fake news using LDA and finding similar kind of documents 

We trained an LDA model on the corpus of fake news to see what topics emerge. Then we test hold out documents to infer their topic distributions and compare them to the rest of the corpus to find the most similar documents.  
We use the gensim package to do this, as it is highly optimised in C and has many features that make the implementation easy to use and very flexible.

### Conclusion
- After cleaning the corpus and keeping only the top 20,000 words, we reduced the unique words in the corpus by 83%
- The LDA model was able to accurately identify different topics in the fake news corpus. We visually inspected these topics to see that the top words were related
- We were able to infer a topic distribution from a new unseen document
- We quickly retrieved the most similar documents in the trained corpus when comparing to the new unseen document. These most similar documents were in fact closely related to the query document
