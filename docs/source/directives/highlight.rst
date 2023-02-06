Highlight
=========================
  
Raw reStructuredText:
::

  .. highlight:: html
  
  The literal blocks are now highlighted as HTML, until a new directive is found.
  
  ::
  
     <html><head></head>
     <body>This is a text.</body>
     </html>
  
  The following directive changes the hightlight language to SQL.
  
  .. highlight:: sql
  
  ::
  
     SELECT * FROM mytable
  
  .. highlight:: none
  
  From here on no highlighting will be done.
  
  ::
  
     SELECT * FROM mytable
  
Typical result:  

.. highlight:: html

The literal blocks are now highlighted as HTML, until a new directive is found.

::

   <html><head></head>
   <body>This is a text.</body>
   </html>

The following directive changes the hightlight language to SQL.

.. highlight:: sql

::

   SELECT * FROM mytable

.. highlight:: none

From here on no highlighting will be done.

::

   SELECT * FROM mytable

