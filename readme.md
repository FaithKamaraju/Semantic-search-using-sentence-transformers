# Semantic Search over Godot Docs using Sentence Transformers

I want a semantic search engine over godot documentation so that I can integrate it into a RAG pipeline that specializes in generating accurate godot help text.

I started experimenting with sentence transformers and the retrieve and re-rank pipelines in "retrieve_rerank.ipynb" notebook. Its just a simple semantic search engine over a subset of wikipedia articles. Even such a simple system blew me away with the results.

I tried out the pre-trained models provided by sbert over the godot docs. The results were not that amazing as expected.

I'm planning to use Generative psuedo labelling (GPL) to domain adapt the base pre-trained models over godot specific language. I hope this improves the performance of the semantic search by quite a bit.