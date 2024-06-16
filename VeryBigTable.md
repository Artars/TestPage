# SPARQL

```SPARQL
PREFIX arco-cd: <https://w3id.org/arco/ontology/context-description/>
PREFIX cis: <http://dati.beniculturali.it/cis/>
SELECT ?collection ?item
WHERE {
 ?collection a cis:CollectionCulEnt.
 ?collection arco-cd:isCollectionIn ?collectionmemb.
 ?collectionmemb arco-cd:hasMemberOfCollection ?item.
} LIMIT 10
```

# Result
<details open>
  <summary>Click here to see results</summary>
<table class="table table-striped table-sm table-borderless">
  <tbody><tr>
    <th>collection</th>
    <th>item</th>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/museo-di-strumentaria-medica-siena-fisiologia">https://w3id.org/arco/resource/CollectionCulEnt/museo-di-strumentaria-medica-siena-fisiologia</a></td>
    <td><a href="https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0900753118">https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0900753118</a></td>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/museo-di-strumentaria-medica-siena-fisiologia">https://w3id.org/arco/resource/CollectionCulEnt/museo-di-strumentaria-medica-siena-fisiologia</a></td>
    <td><a href="https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0900753173">https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0900753173</a></td>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/museo-di-strumentaria-medica-siena-fisiologia">https://w3id.org/arco/resource/CollectionCulEnt/museo-di-strumentaria-medica-siena-fisiologia</a></td>
    <td><a href="https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0900753176">https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0900753176</a></td>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-aldrovandi">https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-aldrovandi</a></td>
    <td><a href="https://w3id.org/arco/resource/DemoEthnoAnthropologicalHeritage/0800688526">https://w3id.org/arco/resource/DemoEthnoAnthropologicalHeritage/0800688526</a></td>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-aldrovandi">https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-aldrovandi</a></td>
    <td><a href="https://w3id.org/arco/resource/DemoEthnoAnthropologicalHeritage/0800688537">https://w3id.org/arco/resource/DemoEthnoAnthropologicalHeritage/0800688537</a></td>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili">https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili</a></td>
    <td><a href="https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691111">https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691111</a></td>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili">https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili</a></td>
    <td><a href="https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691112">https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691112</a></td>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili">https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili</a></td>
    <td><a href="https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691113">https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691113</a></td>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili">https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili</a></td>
    <td><a href="https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691114">https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691114</a></td>
  </tr>
  <tr>
    <td><a href="https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili">https://w3id.org/arco/resource/CollectionCulEnt/-bologna-collezione-marsili</a></td>
    <td><a href="https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691115">https://w3id.org/arco/resource/ScientificOrTechnologicalHeritage/0800691115</a></td>
  </tr>
</tbody></table>
</details>
