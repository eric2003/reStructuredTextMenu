Explicit Markup
================

Explicit markup blocks are used for constructs which float (footnotes), have no direct paper-document representation (hyperlink targets, comments), or require specialized processing (directives). They all begin with two periods and whitespace, the "explicit markup start".

Footnotes
-------------

Raw reStructuredText:
::

  Footnote references, like [5]_.
  Note that footnotes may get
  rearranged, e.g., to the bottom of
  the "page".
  
  .. [5] A numerical footnote. Note
     there's no colon after the ``]``.
  
Typical result:  

Footnote references, like [5]_.
Note that footnotes may get
rearranged, e.g., to the bottom of
the "page".

.. [5] A numerical footnote. Note
   there's no colon after the ``]``.
   
Raw reStructuredText:
::

  Autonumbered footnotes are
  possible, like using [#]_ and [#]_.
  
  .. [#] This is the first one.
  .. [#] This is the second one.
  
  They may be assigned 'autonumber
  labels' - for instance,
  [#fourth]_ and [#third]_.
  
  .. [#third] a.k.a. third_
  
  .. [#fourth] a.k.a. fourth_
  
Typical result:  

Autonumbered footnotes are
possible, like using [#]_ and [#]_.

.. [#] This is the first one.
.. [#] This is the second one.

They may be assigned 'autonumber
labels' - for instance,
[#fourth]_ and [#third]_.

.. [#third] a.k.a. third_

.. [#fourth] a.k.a. fourth_


Raw reStructuredText:
::

  Auto-symbol footnotes are also
  possible, like this: [*]_ and [*]_.
  
  .. [*] This is the first one.
  .. [*] This is the second one.
    
Typical result:  

Auto-symbol footnotes are also
possible, like this: [*]_ and [*]_.

.. [*] This is the first one.
.. [*] This is the second one.

Citations
-------------

Raw reStructuredText:
::

  Citation references, like [CIT2002]_.
  Note that citations may get
  rearranged, e.g., to the bottom of
  the "page".
  
  .. [CIT2002] A citation
     (as often used in journals).
  
  Citation labels contain alphanumerics,
  underlines, hyphens and fullstops.
  Case is not significant.
  
  Given a citation like [this]_, one
  can also refer to it like this_.
  
  .. [this] here.
  
Typical result:  

Citation references, like [CIT2002]_.
Note that citations may get
rearranged, e.g., to the bottom of
the "page".

.. [CIT2002] A citation
   (as often used in journals).

Citation labels contain alphanumerics,
underlines, hyphens and fullstops.
Case is not significant.

Given a citation like [this]_, one
can also refer to it like this_.

.. [this] here.