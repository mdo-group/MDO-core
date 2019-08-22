# Medical Device Ontology Core (MDO-core)
A domain specific ontology that provides the *framework* for describing **Medical Devices**. 

## Medical Device
A **[medical device](https://en.wikipedia.org/w/index.php?title=Medical_device)** is any device intended to be used for medical purposes. Thus what differentiates a medical device from an everyday device is its intended use. *[(wikipedia)](https://en.wikipedia.org/w/index.php?title=Medical_device)*

## Scope
**MDO-core** is designed to be a small ontology, perhaps less than 100 classes and relations describing the common features across a wide variety of medical devices. *Sub-domain ontologies* can extend the MDO-core to describe specific devices in detail. 

## Namespaces
MDO-core `ontology IRI`: http://purl.obolibrary.org/obo/MDO-core.owl 

MDO-core `terms` will use the following namespace pattern:

http://purl.obolibrary.org/obo/MDOC_nnnnnnn
```
MDOC_    = term prefix
nnnnnnn  = unique natural number (range 0000001 to 9999999) - padded with leading 0s. 
```
## Files
```
├── LICENSE
├── README.md
├── docs
├── lib
│   └── ontology     ;; for imported ontology (modules)
├── releases
└── src
    └── ontology
        └── mdo-core.owl
```