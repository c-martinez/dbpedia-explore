# dbpedia-explore
This repo contains [a SPARQL query](DBPedia.rq) which creates a [grlc API](https://github.com/c-martinez/dbpedia-explore) to help explore DBPedia entries.

This query allows to define the subject, predicate and the object to be inspected. All of these are optional, so they may or may not be present. This allows queries to have the flexibility to search explore triples in a flexible way. It always fetches labels (in English) for subject, predicate and object. It also filters by the subject's label.

For example you can search for things that are of [rdf:type](https://www.w3.org/1999/02/22-rdf-syntax-ns#type) [dbo:Band](http://dbpedia.org/ontology/Band) or for things which have a [dbo:hometown](http://dbpedia.org/ontology/hometown) [dbr:Liverpool](http://dbpedia.org/resource/Liverpool)

There is a [notebook](https://github.com/c-martinez/dbpedia-explore/blob/main/Explore%20DBpedia.ipynb) with an exampleof the idealised workflow that could be used to explore concepts on DBPedia.
