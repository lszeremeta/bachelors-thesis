# Buforowanie trójek w magazynach grafów RDF

**Title in English**: Caching triples in RDF graph stores

## Streszczenie
Internet, używany przez nas na co dzień, nie był tworzony do komfortowej analizy danych, a raczej wymiany dokumentów. Odpowiedzą na ten stan rzeczy, zdaje się być projekt Semantycznego Internetu oraz Danych Połączonych. Dzięki temu podejściu do globalnej pajęczyny, możemy konstruować konkretne zapytania oraz uzyskiwać przydatne informacje bez większego wysiłku. W pracy zostaną omówione zagadnienia związane z Semantycznym Internetem, Danymi Połączonymi, RDF-em będącym językiem opisu modelu danych, różnymi serializacjami RDF oraz koncepcjami buforowania danych w bazach danych. Oprócz tego zostanie zaprezentowany RTriples - kompletny magazyn grafów RDF zbudowany w oparciu o bazę danych NoSQL, przystosowaną do zastosowań związanych z Semantycznym Internetem i Danymi Połączonymi. Całość została uzupełniona o testy wydajnościowe zaprezentowanego rozwiązania.

**Słowa kluczowe**: Semantyczny Internet, Dane Połączone, RDF, JSON, buforowanie, indeksy, NoSQL, RethinkDB, RTriples, języki zapytań, bazy danych


## Abstract
Internet used by us every day was not originally created for convenient data analysis, but rather for exchange documents. The answer for this state of affairs seems to be Semantic Web and Linked Data projects. Using this approach to World Wide Web, we can construct certain search queries and obtain useful information without much effort. This work discussed issues related to the Semantic Web, Linked Data, RDF (language describing data model), different RDF serializations and database data caching concepts. In addition, I present RTriples - complete RDF graph store based on NoSQL database, adapted for use in Semantic Web and Linked Data environments. The whole is supplemented by performance tests of presented solution.

**Keywords**: Semantic Web, Linked Data, RDF, JSON, caching, indexes, NoSQL, RethinkDB, RTriples, query languages, databases


## BibTeX

```
@mastersthesis{Szeremeta:Thesis:2015,
	address = "Poland",
	author = "Szeremeta, {\L}ukasz",
	note = "\url{https://github.com/lszeremeta/bachelors-thesis/raw/master/Buforowanie\%20tr\%C3\%B3jek\%20w\%20magazynach\%20graf\%C3\%B3w\%20RDF\%20-\%20\%C5\%81ukasz\%20Szeremeta\%202015.pdf}",
	school = "University of Bialystok",
	title = "{Buforowanie tr{\'o}jek w magazynach graf{\'o}w {RDF}}",
	type = "{Bachelor{\rq}s Thesis}",
	year = "2015"
}
```


## Related repositories

* [RTriples](https://github.com/lszeremeta/RTriples) - Simple but powerful RDF graph store based on awesome RethinkDB database & Ruby projects like Sinatra.
* [bsbmtools-json](https://github.com/lszeremeta/bsbmtools-json) - BSBM Tools with RDF/JSON serialization
* [bsbmtools-json-samples](https://github.com/lszeremeta/bsbmtools-json-samples) - BSBM Tools with RDF/JSON serialization (sample data)

## Author

Copyright (C) 2015 [Łukasz Szeremeta](https://github.com/lszeremeta).

All rights reserved.
