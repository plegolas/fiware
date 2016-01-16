.. AuthZForce documentation master file, created by
   sphinx-quickstart on Wed Sep 30 14:53:18 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

============
Introduction
============

AuthZForce is the reference implementation of the Authorization PDP Generic Enabler (formerly called Access Control GE). Indeed, as mandated by the GE specification, this implementation provides an API to get authorization decisions based on authorization policies, and authorization requests from PEPs. The API follows the REST architecture style, and complies with XACML v3.0. XACML (eXtensible Access Control Markup Language) is a OASIS standard for authorization policy format and evaluation logic, as well as for the authorization decision request/response format. The PDP (Policy Decision Point) and the PEP (Policy Enforcement Point) terms are defined in the XACML standard. This GEri plays the role of a PDP.

To fulfill the XACML architecture, you may need a PEP (Policy Enforcement Point) to protect your application, which is not provided here. For REST APIs, we can use the PEP Proxy (Wilma) available in the FIWARE `catalogue <http://catalogue.fiware.org/enablers/pep-proxy-wilma>`_. 

.. toctree::
   :maxdepth: 4
   
   UserAndProgrammersGuide.rst


.. Indices and tables
.. ==================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`

