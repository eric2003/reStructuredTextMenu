Hyperlink Targets
=========================

External Hyperlink Targets
---------------------------

Raw reStructuredText:
::

  External hyperlinks, like Python_.
  
  .. _Python: https://www.python.org/
  
Typical result:  

External hyperlinks, like Python_.

.. _Python: https://www.python.org/

Internal Hyperlink Targets
---------------------------

Raw reStructuredText:
::

  Internal cross-references, like example_.
  
  .. _example:

  This is an example cross-reference target.
  
Typical result:  

Internal cross-references, like example_.

.. _example:

This is an example cross-reference target.

Indirect Hyperlink Targets
---------------------------

Raw reStructuredText:
::

  Python_ is `my favourite
  programming language`__.
  
  .. _Python: https://www.python.org/
  
  __ Python_
  
Typical result:  

Python_ is `my favourite
programming language`__.

.. _Python: https://www.python.org/

__ Python_

Implicit Hyperlink Targets
---------------------------

Raw reStructuredText:
::

  Titles are targets, too
  =======================
  Implicit references, like `Titles are
  targets, too`_.
  
Typical result:  

Titles are targets, too
=======================
Implicit references, like `Titles are
targets, too`_.

