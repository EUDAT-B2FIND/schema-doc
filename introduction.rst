Introduction
------------

Aim
^^^
The EUDAT Core Metadata Schema defines and describes metadata for research output in order to transfer metadata information through different EUDAT CDI services. It originated from the need to define a common schema that allows to harmonise metadata elements used for storage, publication and discovery of digital research objects across EUDAT partners and beyond. You can access the EUDAT Core Metadata Schema `here <https://gitlab.eudat.eu/eudat-metadata-schema/schema-definitions/-/tree/master>`_ on GitLab.

Scope
^^^^^
Research data management has become an important factor of scientific practice, commonly accepting that good metadata management is crucial for making research data FAIR - findable, accessible, interoperable and reusable. Hence a lot of metadata schemas and standards exist, for specific research areas as well as for generic use. As EUDAT offers data management services for interdisciplinary research, only a generic schema is applicable. The EUDAT Core metadata elements described here can be seen as a *minimum* set of metadata elements being transferred between EUDAT services. 

While EUDAT Core is based on the `DataCite Metadata Schema <https://schema.datacite.org/>`_ 4.4 and the `OpenAire Guidelines for Data Archives <https://guidelines.openaire.eu/en/latest/data/index.html>`_ to ensure interoperability with these important standards, there are some specific differences due to practical needs:

* Unlike DataCite, EUDAT Core accepts other persistent identifier schemes and not only a DOI in :ref:`d:identifier`
* In contrast to DataCite and OpenAire, in EUDAT Core only four metadata elements are mandatory: Identifier, Title, Publisher and PublicationYear
* EUDAT Core includes additional metadata elements, namely: Discipline, Contact, Instrument and TemporalCoverage.

Usage
^^^^^

The EUDAT Core metadata schema is used to standardise and validate exchange of metadata fields and values between, from and to EUDAT storage services. This is typically done using Extensible Markup Language (XML) formatted documents. The EUDAT Core metadata schema can be used in any XML document by explicitly referring to the corresponding XML Schema Definition (XSD) file that specifies the allowed fields and values.

In order to make sure your document validates with the schema, the schema location attribute has to be included in the document’s root element. The value must include the namespace and one or more (alternative) URLs of the schema publication location and a version indicator, e.g. <http://schema.eudat.eu/schema/kernel-1 http://schema.eudat.eu/meta/kernel-core-1.0/schema.xsd>.

If you are using multiple schema definitions in a single document, make sure to define a unique namespace for the EUDAT Core metadata schema.

See the GitLab repository for `EUDAT metadata schema examples <https://gitlab.eudat.eu/eudat-metadata-schema/schema-definitions/-/tree/master/examples>`_.

.. note::
   Even though the EUDAT Core Metadata Schema was developed for streamlining metadata transfer across EUDAT services, of course it may be used by everyone to exchange metadata. For that, we strongly recommend using standardised vocabularies wherever possible. However, in order to make as much research output as possible searchable and findable, only few elements are mandatory and only few elements require specific attributes.
