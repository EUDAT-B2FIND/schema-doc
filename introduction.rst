Introduction
------------

Aim
^^^
The EUDAT Core Metadata Schema defines and describes metadata for research output in order to transfer metadata information through different EUDAT CDI services. It originates from the need to define a common schema that allows to harmonize metadata elements used for storage, publication and discovery of digital research objects across EUDAT partners and beyond. 

Scope
^^^^^
Research data management has become an important factor of scientific practice, commonly accepting that good metadata management is crucial for making research data FAIR - findable, accessible, interoperable and reusable. Hence a lot of metadata schemas and standards exist, for specific research areas as well as such for generic use. As EUDAT offers data management services for interdisciplinary research, only a generic schema is applicable: the schema described here can be seen as a *minimum* set of metadata elements. 

While EUDAT Core is based on the `Datacite Metadata Schema <https://schema.datacite.org/>`_ 4.3 and the `OpenAire Guidelines for Data Archives <https://guidelines.openaire.eu/en/latest/data/index.html>`_, there are some specific differences due to practical needs:
* EUDAT Core accepts other persistent identifier schemes and not only a DOI in :ref:`d:identifier`
* in contrast to Datacite and OpenAire, in EUDAT Core only four metadata elements are mandatory: Identifier, Title, Publisher and PublicationYear
* EUDAT Core includes additional metadata elements, namely: Discipline, Contact, Instrument and TemporalCoverage. 

.. note::
   Even though the EUDAT Core Metadata Schema is developed for transferring metadata across EUDAT services, of course it may be used by everyone to exchange metadata. For that, we strongly recommend using standardised vocabularies wherever possible. However, in order to make as much research output as possible searchable and findable, only few elements are mandatory and only few elements require specific attributes.
