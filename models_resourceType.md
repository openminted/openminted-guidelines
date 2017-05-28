#### resourceType
##### Usage
Mandatory
##### Type
Closed controlled vocabulary
##### Attributes
 
##### Controlled vocabulary reference and/or values
ms:resourceType: _corpus_, _lexicalConceptualResource_, _languageDescription_, _model_, _component_
##### Definition/Explanations
Specifies the type of the resource being described or the type of the resource that a tool or service takes as input or produces as output
##### Recommended usage
For models, the fixed value "languageDescription" (combined with languageDescriptiontype "mlModel") must be added automatically
##### Relation to other metadata schemas
* **DCMI:** skos:narrowMatch dct:type
* **DataCite 4.0:** skos:closeMatch datacite:resourceTypeGeneral & datacite:resourceType; recommended usage for models is to use "model" but the value "dataset" can also be used
