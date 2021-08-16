.. _d:temporalcoverage:

Temporal Coverage (O)
---------------------
Period of time the research data is related to (occurence: 0-n). Could be a date format or plain text.

**Allowed values, examples, other constraints**

YYYY, YYYY-MM-DD, YYYY-MM-DDThh:mm:ssTZD or any other format or level of granularity described in W3CDTF. Years before 0000 must be prefixed with a - sign, e.g., -0054 to indicate 55 BC.


Example
~~~~~~~
.. code-block:: xml
   :linenos:

   <temporalCoverages>
      <temporalCoverage>
          <startDate format="ISO-8601">2004-03-02</startDate>
          <endDate format="ISO-8601">2005-06-02</endDate>
      </temporalCoverage>
      <temporalCoverage>
          <span>Paleocene</span>
      </temporalCoverage>
  </temporalCoverages>
