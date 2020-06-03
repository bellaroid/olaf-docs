================================
Welcome to Olaf's documentation!
================================

.. toctree::
   :caption: Table of Contents
   :name: mastertoc

   content/setup.rst

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
* :ref:`setup`

***********************
Overview of the Project
***********************

Olaf is a Python JSONRPC framework inspired largely by Odoo.
However, it's not meant to be compatible or even alike to it,
but it's gonna feel comfortable for sure if you are used to work 
with such a great tool.

Key Features
============
* **Object Document Mapping**
   Olaf is bundled with a data abstraction layer around **MongoDB**.
   Despite using a non-relational database engine, Olaf is capable of handling complex 
   relations between your data models, such as Many-to-One, One-to-Many and Many-to-Many.
* **Modularity**
   Your code can be bundled in Python modules so they can be shared or reused.
* **Security**
   Olaf includes PyJWT for restricting unwanted access to your data resources. Once
   a user is authenticated, data access can still be restricted by group directives, 
   model-level access rules and even document-level access rules.




