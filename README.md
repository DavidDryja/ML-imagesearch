This is a project uses machine learning to do an image search.

-This project uses CLIP's pre-trained neural network (Downloaded using Hugging Face)

-It downloads images from an image database (from Imagenette)

-The CLIP model allows us to generate embeddings (images turned into meaningful vectors) for each picture

-All of the embeddings are stored in a vector database (using Pinecone)

-Using a new picture with new embeddings the vector database is queried to find the most similar pictures.

-The most similar pictures are displayed and the image path is used to determine the category of picture.

David Dryja