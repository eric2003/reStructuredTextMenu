CSV Table
=========================

Raw reStructuredText:
::

  .. csv-table::
     :header: "Header 1", "Header 2", "Header 3"
     :widths: 25 25 50
     :delim: ;
  
     Data 1; Data 2; Data 3
     Data 4; Data 5; Data 6
 
Typical result:  

.. csv-table::
   :header: "Header 1", "Header 2", "Header 3"
   :widths: 25 25 50
   :delim: ;

   Data 1; Data 2; Data 3
   Data 4; Data 5; Data 6
   
Raw reStructuredText:
::

  .. csv-table:: Frozen Delights!
     :header: "Treat", "Quantity", "Description"
     :widths: 15, 10, 30
  
     "Albatross", 2.99, "On a stick!"
     "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
     crunchy, now would it?"
     "Gannet Ripple", 1.99, "On a stick!"
 
Typical result:  

.. csv-table:: Frozen Delights!
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"  


