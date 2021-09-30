.. _d:fundingreference:

FundingReference (O)
--------------------
Information about financial support (funding) for the resource(occurrences: 0-n).

**Allowed values, examples, other constraints**

Could be funder name and/or award number: BMBF, 01UG1774X ; DFG.

Example
~~~~~~~
.. code-block:: xml
   :linenos:

   <fundingReferences>
      <fundingReference>
          <funderName>National Science Foundation</funderName>
          <awardNumber>XYZ-10001</awardNumber>
      </fundingReference>
      <fundingReference>
          <funderName>Federal Science Organisation</funderName>
      </fundingReference>
  </fundingReferences>

