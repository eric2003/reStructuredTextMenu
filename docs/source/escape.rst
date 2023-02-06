Escaping with Backslashes
=========================

reStructuredText uses backslashes ("\\") to override the special meaning given to markup characters and get the literal characters themselves. To get a literal backslash, use an escaped backslash ("\\\\"). For example:

Raw reStructuredText:
::

*escape* ``with`` "\"

Typical result:

*escape* ``with`` "\"

Raw reStructuredText:
::

\*escape* \``with`` "\\"

Typical result:

\*escape* \``with`` "\\"



