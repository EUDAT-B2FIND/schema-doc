.. _d:discipline:

Discipline (O)
--------------
The research discipline(s) the resource can be categorized in (occurrence: 0-n). B2FIND automatically sorts records into disciplines according to the keywords of the record by matching them to the `B2FIND disciplines classification <https://github.com/EUDAT-B2FIND/md-ingestion/blob/master/etc/b2find_disciplines.json>`__. If no keywords are provided in the metadata, the default discipline is "Other". However, it can also be set to a specific term matching the research community's needs.

**Allowed values, examples, other constraints**

Biological and Biomimetic Chemistry ; Food Sciences

Example
~~~~~~~
.. code-block:: xml
   :linenos:

  <disciplines>
    <discipline>
     Biological and Biomimetic Chemistry
    </discipline>
    <discipline>
    Food Sciences
    </discipline>
  <disciplines>
