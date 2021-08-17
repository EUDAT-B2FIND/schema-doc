.. _d:relatedidentifier:

RelatedIdentifier (O)
---------------------
Identifiers of related resources (occurrence: 0-n).

**Allowed values, examples, other constraints**

Should be a resolvable URI.

Example
~~~~~~~
.. code-block:: xml
   :linenos:

   <relatedIdentifiers>
      <relatedIdentifier relatedIdentifierType="URL">url:https://schema.eudat.eu/application/citeproc+json/10.12345/eudat-core-example-full</relatedIdentifier>
      <relatedIdentifier relatedIdentifierType="arXiv">arXiv:0706.0001</relatedIdentifier>
   </relatedIdentifiers>

