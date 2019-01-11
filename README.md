# whoosh-search
Example of indexing a pandas dataframe to whoosh.
Here we do this to search the Brown Corpus.

The Whoosh package was built by Matt Chaput.
This is a pure python search engine.
You can read more about it here:
https://whoosh.readthedocs.io/en/latest/intro.html#

The Brown Corpus is a main staple of natural language processing.
https://en.wikipedia.org/wiki/Brown_Corpus

Here, this utility and data set are integrated using Jupyter Notebook.
There's three components needed to do this.
1) A index build notebook that imports data into pandas and indexes it for whoosh.
2) An indexdir folder to hold the index.
3) A search notebook that uses the index to provide the search utility.

We import the Brown Corpus into Pandas, index it, and provide a search tool.


