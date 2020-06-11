
## DeepWalk
- random walks 
- skip-gram
- maximize posterior probability of observing neighboring vertex in random walk 

## GraRep 
- SVD on log-transformed DeepWalk transition probability matrix of multiple different orders 
- concatenate these embeddings 

## LINE
- similar to DeepWalk

## Node2Vec
- similar to DeepWalk with added parameters to tune the random walks

## Hope
- some kind of large matrix factorization

## Verse 
- minimize KL divergence between some similarity computed on the graph and one computed on the embedding 
- can use personalized PageRank, adjacency, others 
- obj-func reduces to cross-entropy loss 
- uses "Noise Contrastice Estimation" to approximate loss function for SGD. Unsure what this is.
