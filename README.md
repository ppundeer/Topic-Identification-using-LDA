# Topic-Identification-using-LDA
Identifying topic of fake news using LDA and finding similar kind of documents 

We trained an LDA model on the corpus of fake news to see what topics emerge. Then we test hold out documents to infer their topic distributions and compare them to the rest of the corpus to find the most similar documents.  
We use the gensim package to do this, as it is highly optimised in C and has many features that make the implementation easy to use and very flexible.
