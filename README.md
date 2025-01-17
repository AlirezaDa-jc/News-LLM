# News LLM
### This Project contains three submodules
- util : This is the implementation for rag system using weaviate, ollama and dataset(https://www.kaggle.com/datasets/rmisra/news-category-dataset). You can create your collection, populate db (GPU and Unoptimized in cpu), and call simples queries. Custom modules has been created, commands and their module files are available in ollama-models directory 
- backend : This is a simple Flask Api for integrating with weaviate. 
- front : This is Front end using Next Js and Tailwind for backend to call the flask api and get results based on keywords and responses from generative ai.
