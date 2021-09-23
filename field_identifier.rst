.. _d:identifier:

Identifier (M)
--------------
A unique string that identifies the resource, ideally persistent (occurrences: 1-n). To supply alternate identifiers, repeat this property. Use attributes for defining the identifier type, e.g. "DOI", 'Handle', 'URL' or other types. For allowed values, see controlled `list of identifier types <https://gitlab.eudat.eu/eudat-metadata-schema/schema-definitions/-/blob/master/include/eudat-identifierType-v1.xsd>`_.

Example
~~~~~~~
.. code-block:: xml
   :linenos:

   <identifiers>
      <identifier identifierType="DOI">10.1594/WDCC/CCSRNIES_SRES_B2</identifier>
      <identifier identifierType="ARK">2013A&amp;A...558A.149B</identifier>
      <identifier identifierType="URL">https://b2share.eudat.eu/records/bb8964ff899c4711a0e8875b87ab2800</identifier>
   </identifiers>
