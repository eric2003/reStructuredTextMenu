Inline Markup
================

Emphasis
-------------

Raw reStructuredText:
::

  Doctree element: emphasis.
  
  Start-string = end-string = "*".
  
  Text enclosed by single asterisk characters is emphasized:
  
  This is *emphasized text*.
  
  Emphasized text is typically displayed in italics.
  
Typical result:  

Doctree element: emphasis.

Start-string = end-string = "*".

Text enclosed by single asterisk characters is emphasized:

This is *emphasized text*.

Emphasized text is typically displayed in italics.

Strong Emphasis
----------------

Raw reStructuredText:
::

  Doctree element: strong.
  
  Start-string = end-string = "**".
  
  Text enclosed by double-asterisks is emphasized strongly:
  
  This is **strong text**.
  
  Strongly emphasized text is typically displayed in boldface.
  
Typical result:  

Doctree element: strong.

Start-string = end-string = "**".

Text enclosed by double-asterisks is emphasized strongly:

This is **strong text**.

Strongly emphasized text is typically displayed in boldface.


Interpreted Text
----------------

Raw reStructuredText:
::

  Doctree element: depends on the explicit or implicit role and processing.
  
  Start-string = end-string = "`".
  
  Interpreted text is text that is meant to be related, indexed, linked, summarized, or otherwise processed, but the text itself is typically left alone. Interpreted text is enclosed by single backquote characters:
  
  This is `interpreted text`.
  
Typical result:  

Doctree element: depends on the explicit or implicit role and processing.

Start-string = end-string = "`".

Interpreted text is text that is meant to be related, indexed, linked, summarized, or otherwise processed, but the text itself is typically left alone. Interpreted text is enclosed by single backquote characters:

This is `interpreted text`.

Inline Literals
----------------

Raw reStructuredText:
::

  Doctree element: literal.
  
  Start-string = end-string = "``".
  
  Text enclosed by double-backquotes is treated as inline literals:
  
  This text is an example of ``inline literals``.
  
  Inline literals may contain any characters except two adjacent backquotes in an end-string context (according to the recognition rules above). No markup interpretation (including backslash-escape interpretation) is done within inline literals.
  
  Line breaks and sequences of whitespace characters are not protected in inline literals. Although a reStructuredText parser will preserve them in its output, the final representation of the processed document depends on the output formatter, thus the preservation of whitespace cannot be guaranteed. If the preservation of line breaks and/or other whitespace is important, literal blocks should be used.
  
  Inline literals are useful for short code snippets. For example:
  
  The regular expression ``[+-]?(\d+(\.\d*)?|\.\d+)`` matches
  
  floating-point numbers (without exponents).
  
Typical result:  

Doctree element: literal.

Start-string = end-string = "``".

Text enclosed by double-backquotes is treated as inline literals:

This text is an example of ``inline literals``.

Inline literals may contain any characters except two adjacent backquotes in an end-string context (according to the recognition rules above). No markup interpretation (including backslash-escape interpretation) is done within inline literals.

Line breaks and sequences of whitespace characters are not protected in inline literals. Although a reStructuredText parser will preserve them in its output, the final representation of the processed document depends on the output formatter, thus the preservation of whitespace cannot be guaranteed. If the preservation of line breaks and/or other whitespace is important, literal blocks should be used.

Inline literals are useful for short code snippets. For example:

The regular expression ``[+-]?(\d+(\.\d*)?|\.\d+)`` matches

floating-point numbers (without exponents).


.. toctree::
   :maxdepth: 2
   
   /inline-markup/hyperlink
