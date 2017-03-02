### How ** to document your components** {#documentation-metadata-requirements}

To be fully compatible with OpenMinTeD, you must

* ensure that the software is distributed under a perpetual, world-wide, no-charge, royalty-free copyright/patent licence that permits unrestricted use and allows unlimited redistribution
* include in the metadata record a link to the licence document\(s\) with the terms and conditions under which it is provided, and attach the licence document\(s\) together with the resource
* if you already have a PID for your resource \(e.g. a URI or a HANDLE\), make sure it is included in the metadata record \(cf. [identifier](/publications_identifier.md) for more information\)
* ensure that you version all your s/w resources and label the versions in an unambiguous way, preferably following the [Semantic Versioning recommendations](http://semver.org).
* ensure that you provide with your s/w resource appropriate machine-readable metadata embedded in the source code \(where possible\) and according to the relevant framework \(e.g. uimaFIT Java annotations etc.\); make sure that the metadata descriptors are properly identified an unambiguous way that makes them easy to distinguish and extract
* for Java-based components, ensure that you use the Java fully qualified class naming conventions for naming your components; together with the Maven practices for registering packaging and version, this contributes to unique identifiers of the components
* describe all the executional requirements for the proper operation of the software, i.e. required software libraries, ancillary resources, annotation schema dependencies etc.
* describe the input and output requirements for your software, at least as regards the type of resource, the language \(if required\), data format and character encoding, and annotation types of the input/output resource
* declare whether the software is downloadable or can only be accessed as a web service in the metadata.
* ensure that you describe appropriately the functionalities of the software, both through the OMTD-SHARE [component type ](/components_componentType.md)vocabulary as well as in a free text description, supplying more information for the user.

Further recommendations that contribute to interoperability include the following:

* It is important that you provide the appropriate documentation for your resource \(e.g. manuals, help files etc.\), which you should also version along with the software and add as reference to your metadata record.
* Recommend one of the publications about your resource as the one to be cited for scholarly attribution and add this information in the metadata record.
* Make sure that you fill in the metadata record all the elements required for citing your resource[^1], i.e. the creator of the resource, a title, the resource type and an identifier, and optionally, the publication date, the version and the publisher or distributor of
* In all cases, where linking to other resources or entities \(e.g. persons, projects etc.\), please try to do this through unique and persistent identifiers of authority lists and sources, to the extent possible, documenting also the authority and/or scheme it adheres to.

---

[^1] For citation, OpenMinTeD endorses the [Joint Declaration of Data Citation Principles](https://www.force11.org/group/joint-declaration-data-citation-principles-final), as well as the more specialised [RDA recommendations for data citation of evolving data](https://www.rd-alliance.org/system/files/RDA-DC-Recommendations_151020.pdf) and [DataCite guidelines](https://www.datacite.org/cite-your-data.html).

