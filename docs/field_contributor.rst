.. _d:contributor:

7. Contributor (O)
---------------------
The institution or person or instrument responsible for collecting, managing, distributing, or otherwise contributing to the development of the resource. (occurrences: 0-n).

**Allowed values, examples, other constraints**

.. note::

   OpenAIRE uses this property to allow unique and persistent identification of the funder who has funded wholly or partly the dataset described. This does not exclude also using this property for additional contributors as defined by DataCite Metadata Schema.

   The property and sub-properties are only *mandatory when applicable (MA)* for describing funding information. Further use is *optional (O)*.

   Please refer to the section :ref:`fundinginfo` for a complete example of the use of :ref:`d:contributor`, :ref:`d:contributortype`, :ref:`d:contributorname`, :ref:`d:contributor_nameidentifier` and :ref:`d:contributor_nameidentifierscheme` to provide funding information.

.. _d:contributortype:

7.1 contributorType (MA/O)
~~~~~~~~~~~~~~~~~~~~~~~~~~
The type of contributor of the resource (occurrences: 1).

**Allowed values, examples, other constraints**

If :ref:`d:contributor` is used, then :ref:`d:contributortype` is mandatory.

*Controlled List Values:*

* ContactPerson
* DataCollector
* DataCurator
* DataManager
* Distributor
* Editor
* Funder
* HostingInstitution
* Producer
* ProjectLeader
* ProjectManager
* ProjectMember
* RegistrationAgency
* RegistrationAuthority
* RelatedPerson
* Researcher
* ResearchGroup
* RightsHolder
* Sponsor
* Supervisor
* WorkPackageLeader
* Other

.. _d:contributorname:

7.2 contributorName (MA/O)
~~~~~~~~~~~~~~~~~~~~~~~~~~
The name of the contributor (occurrences: 1).

**Allowed values, examples, other constraints**

If :ref:`d:contributor` is used, then :ref:`d:contributorname` is mandatory.

Examples: Patel, Emily; Doe, John

The personal name format may be: family, given. Non-roman names should be transliterated according to the `ALA-LC <http://www.loc.gov/catdir/cpso/roman.html>`_ schemes.

.. note::

   Applicable only when contributorType is â€œFunderâ€:

   Name of the funding entity. Example for European Commission funded research use ``European Commission``, or for Wellcome Trust funded research use ``Wellcome Trust``. Specifically do not use the project acronym.

.. _d:contributor_nameidentifier:

7
.. _d:contributor_affiliation:

7.4 affiliation (O)
~~~~~~~~~~~~~~~~~~~
The organizational or institutional affiliation of the contributor (occurrences: 0-n).

**Allowed values, examples, other constraints**

Free text.

