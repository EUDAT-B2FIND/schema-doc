.. _d:identifier:

Identifier (M)
--------------
One or more unique strings that identifiy a single resource, ideally persistent.


.. note::
   The B2FIND GUI ranks identifiers according to their persistency. DOIs will be displayed as "DOI", other persistent identifiers (e.g. Handles) will be displayed as "PID". Any other identifier will be displayed as "Source".
   For usability purposes all identifier are displayed as resolvable links.


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
