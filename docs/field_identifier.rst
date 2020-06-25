.. _d:identifier:

1. Identifier (M)
-----------------
A unique string that identifies a resource, ideally persistent. (occurrences: 1).

**Allowed values, examples, other constraints**

Controlled list values 
    ARK
    DOI
    Handle
    PURL
    URN
    URL

.. note::
   Unlike DataCite, B2FIND allows for DOIs and other types of identifiers.

Example
~~~~~~~
.. code-block:: xml
   :linenos:

	<identifier identiferType="DOI">
	 10.1594/WDCC/CCSRNIES_SRES_B2
	</identifier>

	OR

	<identifier identifierType="ARK">
	 2013A&amp;A...558A.149B
	</identifier>
