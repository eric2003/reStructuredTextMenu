Glossary
=========================
  
Raw reStructuredText:
::

  .. glossary::
  
     environment
        A structure where information about all documents under the root is
        saved, and used for cross-referencing.  The environment is pickled
        after the parsing stage, so that successive runs only need to read
        and parse new and changed documents.
  
     source directory
        The directory which, including its subdirectories, contains all
        source files for one Sphinx project. 
  
Typical result:  

.. glossary::

   environment
      A structure where information about all documents under the root is
      saved, and used for cross-referencing.  The environment is pickled
      after the parsing stage, so that successive runs only need to read
      and parse new and changed documents.

   source directory
      The directory which, including its subdirectories, contains all
      source files for one Sphinx project.

Raw reStructuredText:
::

  .. glossary::
  
     term 1
     term 2
        Definition of both terms. 
  
Typical result:  

.. glossary::

   term 1
   term 2
      Definition of both terms.
 
Raw reStructuredText:
::

  .. glossary::
  
     term 3 : A
     term 4 : B
        Definition of both terms.
  
Typical result:  

.. glossary::

   term 3 : A
   term 4 : B
      Definition of both terms.