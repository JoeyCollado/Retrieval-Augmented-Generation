# query -> embedding model -> vector embedding -> retriever -> chunks -> result 

# query = user query.

# retriever = is going to take all the vector embedding (particular data) from query and go through all the different vector embeddings in the ingestion pipeline (comparing).

# chunks = the resulted data that are taken from the similar vectors from the vector embedding matchings.
#          vector embedding is used for matching with other vector embeddings