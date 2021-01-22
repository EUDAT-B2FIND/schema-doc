.. _d:identifier:

Identifier (M)
--------------
A unique string that identifies a resource, ideally persistent (occurrence: 1). You can either provide a:

* DOI: A persistent citable identifier that uniquely identifies a resource, registered as DOI.
* PID: A persistent identifier that uniquely identifies a resource, registered at a handle server.
* URI: An identifier that uniquely identifies a resource. It may link to the data itself or a landing page that curates the data.

At least one identifier is mandatory.

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