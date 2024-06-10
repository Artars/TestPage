# My page

Here's my code:

```SPARQL
PREFIX arco-location: <https://w3id.org/arco/ontology/location/>
SELECT *
WHERE {
  ?entity rdfs:label ?entityLabel ; 
    arco-location:hasTimeIndexedTypedLocation ?location .
    ?location arco-location:hasLocationType arco-location:StorageLocation .
  }
limit 100
```
