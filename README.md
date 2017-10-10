CMSC 12300 Project NLP on reddit comments using MapReduce

* Crawled 26 GB dataset of reddit comments in r/Politics
* Combined Entity Extraction, Search of Entities in Google Knowledge Graph, and Sentiment Analysis to come up
with rating tuples of the form (userid, politicalentityid, sentiment)
* Created user x entity Matrix of these ratings and performed dimension reduction and clustering to find
politcal groups, analyze distribution of sentiment for political vs. non-political entities.
* Also retrieved averaged word vectors of comments to perform similarity based clustering  of users based on comments

