# Subreddit-Topic-Visualization

## Synopsis 
This code repository generates a d3 graph with mental health subreddits and shared topics as where a link between a subreddit and topic represents high expression of the topic in that subreddit. In this visualization, only topics that are shared between topics are visualized. 

The data used to plot the graph was generated using an unsupervised topic model (Latent Dirichlet Allocation). I generated a set of 100 topics using ~6 million comments from mental health subreddits and computed which topics were likely to be expressed in each subreddit. 

## Running the Visualization

Start a localhost server using the command `python -m SimpleHTTPServer`

For a visualization with labeled links run the file graphtest2.html in your browser by entering the url `http://localhost8000/graphtest2.html`

For a bipartite graph visualization, run the file bipartite_graph.html in you browser by entering the url `http://localhost8000/bipartite_graph.html`

The labeled link visualization can also be found on [github pages](http://geebioso.github.io/Subreddit-Topic-Visualization/)
