# Build a Semantic Book Recommender with LLMs – Full Course

This repo contains all of the code to complete the freeCodeCamp course, "Build a Semantic Book Recommender with LLMs – Full Course". There are five components to this tutorial:
* Text data cleaning (code in the notebook `data-exploration.ipynb`)
Semantic (vector) search and building a vector database (all code now consolidated into the notebook vector_search.ipynb). This module generates embeddings for all books and performs similarity search, allowing users to find the most relevant books to any natural language query (e.g., "a book about a person seeking revenge").

* Zero-shot text classification using LLMs (included inside `vector_search.ipynb`). This classifies each book as either "fiction" or "non-fiction", creating an additional metadata facet that users can filter on.

* Sentiment and emotion analysis using LLMs (integrated into vector_search.ipynb). This extracts emotional attributes such as joy, suspense, or sadness, enabling users to sort books based on tone and emotional intensity.

* Interactive recommendation dashboard using Gradio. This allows users to interact with the system through a web-based UI, submit queries, apply filters, and view personalized book recommendations.

This project was initially created in Python 3.11. In order to run the project, the following dependencies are required:
* [kagglehub](https://pypi.org/project/kagglehub/)
* [pandas](https://pypi.org/project/pandas/)
* [matplotlib](https://pypi.org/project/matplotlib/)
* [seaborn](https://pypi.org/project/seaborn/)
* [python-dotenv](https://pypi.org/project/python-dotenv/)
* [langchain-community](https://pypi.org/project/langchain-community/)
* [langchain-opencv](https://pypi.org/project/langchain-opencv/)
* [langchain-chroma](https://pypi.org/project/langchain-chroma/)
* [transformers](https://pypi.org/project/transformers/)
* [gradio](https://pypi.org/project/gradio/)
* [notebook](https://pypi.org/project/notebook/)
* [ipywidgets](https://pypi.org/project/ipywidgets/)

A requirements.txt file containing all the project dependencies is provided as part of this repo.

In order to create your vector database, you'll need to create a .env file in your root directory containing your OpenAI API key. Instructions on how to do this are part of the tutorial.
