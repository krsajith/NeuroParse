# NeuroParse

NeuroParse is state of art business intelligence tool for the cognitive Era.

## Modules

### NeuroParseCoreAPI
The core backend API called by NeuroParseUI , developed with spring boot anb java-8.

### NeuroParseNLPService
NLP service developed with spacy open source library , which parse the user input.

### NeuroParseDataService
Datsbase service for fetching data from any RDBMS or NOSql datbase.

### NeuroParseUI
The IDE for NeuroParse.


### Running the service

```
-cd .. /NeuroParseNLPService
-python app.py
```

```
-cd .. /NeuroParseUI
-http-server
```

```
-cd .. /NeuroParseCoreAPI
-java 
```


## Built With

* [spacy](https://spacy.io/docs/usage/) - The opensource NLP library
* [Maven](https://maven.apache.org/) - Dependency Management

## Authors

* **Sajith Rajappan**
* **Kurien Thomas**
* **Joseph Justus**


