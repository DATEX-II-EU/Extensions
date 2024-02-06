Submitted by thilo.schoen on Monday, 3 August, 2009 - 17:24

Status definition refers to ISO 14817
Card

Extension object
CataloguePublication

Extension information
A level B extension for working with catalogues is proposed. A Catalogue contains information about the kind of data a server has to offer. An (identifiable) Catalogue can be published in the new CataloguePublication. It has an optional name and contains CatalogueItems. Each item has an index number and contains information about which kind of data could be delivered by the server (names of identifiable classes) and (optionally) on which locations the data may be referenced. The Catalogue design is intentionally simple to satisfy the basic needs of such a feature without making it too difficult for a server to work with it. The proposal is driven by the OTS 2 project where it is a goal to transport DATEX II data using the OTS 2 protocol. The CataloguePublication is used so a server can offer its data in one or more Catalogues, sub-divided into CatalogueItems. A client then can subscribe to some of these items referencing the (identifiable) Catalogue and the CatalogueItem index numbers. This is intended to be used in OTS 2 protocol for subscriptions to SituationPublications and ElaboratedDataPublications. The full EA Model file and XML Schema which incorporate the proposed new CataloguePublication as an extension are downloadable below. There is also a separate xmi export file containing the Extension package.

Organization name
GEVAS software GmbH

Contact name
Thilo Schön

Organization description
GEVAS software offers software solutions and services for road traffic technology, mobility and information management. It is the objective of GEVAS software to advance road traffic technology and to improve the quality of life in urban agglomerations both economical and ecologically.

Organization logo
![Alt text](image.png)

Contact mail
thilo.schoen@gevas.de

Website
www.gevas.eu

Country/Region
Germany

Centre type
other