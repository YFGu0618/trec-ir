# Relevance Feedback Model

- **PseudoRFRetrievalModel. RetrieveQuery** Given the query, this method can return the `TopN` most relevant documents. This retrieval model is enhanced with the pseudo relevance feedback.
- **PseudoRFRetrievalModel. GetTokenRFScore** For each token in the query, the probability of a term generated by the feedback documents is calculated.
