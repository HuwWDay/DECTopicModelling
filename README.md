# DECTopicModelling
Side project doing various types of topic modelling on content from the Data Ethics Club website

The plan:
1. Find a way to load in all the [DEC writeups](https://dataethicsclub.com/write_ups/write-ups.html) from the website (or the [github](https://github.com/very-good-science/data-ethics-club)?) as data
2. Index them with their dates and other metadata
3. Use [BERTopic for topic modelling](https://maartengr.github.io/BERTopic/index.html), want to write some code for fine tuning parameters for [UMAP](https://umap-learn.readthedocs.io/en/latest/clustering.html) and [HDBSCAN](https://hdbscan.readthedocs.io/en/latest/basic_hdbscan.html)
4. Want to do some dynamic topic modelling and maybe hierarchical as well?
5. Find some cute ways to visualise how the different topics have varied over time
