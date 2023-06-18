# MusicTheoryOntology-KE23
### Done by Juan González Magdalena and Juan Rubio Gómez

For more information here you have the [report]().

### RDF graph
We have designed an ontology where the following information has been included:
![image](https://github.com/juanglezmag/MusicTheory-KE23/assets/136845142/6a89bf30-a7fa-4a00-ad61-ea3b883fc4d7)




### Ontology requirements
The competency questions used to design the ontology are in the [CQ-list](https://github.com/juanglezmag/MusicTheory-KE23/blob/main/test/CQ-list.txt).

For the test of the CQ we have used the [OWL-unit](https://github.com/luigi-asprino/owl-unit).

### Data mapping

The data mapping phase heavily relies on the data provided in the ChoCo repository. We extensively explored the dataset and attempted various CONSTRUCT SPARQL queries to the endpoint offered by the ChoCo repository. Our goal was to obtain a .ttl file (converting the JSON file into the Turtle format) that would contain the data aligned with our ontology , which is commonly used for querying with Sparql-Anything to try our Ontology.

### End-Point

We encountered challenges with the specified data. As a workaround, we utilized a set of
individuals built within Protege, our ontology development tool, to generate queries against the
endpoint. To facilitate this process, we deployed Apache Jena Fuseki, a SPARQL server and
7
endpoint provided by the Apache Jena framework. This powerful solution enabled us to
publish and query RDF data efficiently using the SPARQL query language.


