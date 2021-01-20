.. _d:relatedidentifier:

Related Identifier (O)
----------------------
Identifiers of related resources (occurrence: 0-n).

**Allowed values, examples, other constraints**

*Controlled list values* 
    * ARK
    * DOI
    * Handle
    * PURL
    * URN
    * URL
    * other, community-specific identifier type

.. note::
   Unlike DataCite, B2FIND allows for DOIs and other types of identifiers.

Example
~~~~~~~
.. code-block:: xml
   :linenos:

   <identifiers>
  	<identifier identiferType="DOI">
  	 10.1594/WDCC/CCSRNIES_SRES_B2
  	</identifier>
  	<identifier identifierType="ARK">
  	 2013A&amp;A...558A.149B
  	</identifier>
   </identifiers>