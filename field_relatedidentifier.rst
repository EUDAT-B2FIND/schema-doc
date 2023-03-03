.. _d:relatedidentifier:

RelatedIdentifier (O)
---------------------
Identifier(s) of related resources (occurrence: 0-n).

**Allowed values, examples, other constraints**

For allowed type values, see controlled `list of identifier types <https://gitlab.eudat.eu/eudat-metadata-schema/schema-definitions/-/blob/master/include/eudat-identifierType-v1.xsd>`_.

Example
~~~~~~~
.. code-block:: xml
   :linenos:

   <relatedIdentifiers>
      <relatedIdentifier relatedIdentifierType="URL">url:https://schema.eudat.eu/application/citeproc+json/10.12345/eudat-core-example-full</relatedIdentifier>
      <relatedIdentifier relatedIdentifierType="arXiv">arXiv:0706.0001</relatedIdentifier>
   </relatedIdentifiers>

