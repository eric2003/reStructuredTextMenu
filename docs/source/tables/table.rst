Table
=========================

Grid table
-------------

Raw reStructuredText:
::

  Grid table:
  
  +------------+------------+-----------+
  | Header 1   | Header 2   | Header 3  |
  +============+============+===========+
  | body row 1 | column 2   | column 3  |
  +------------+------------+-----------+
  | body row 2 | Cells may span columns.|
  +------------+------------+-----------+
  | body row 3 | Cells may  | - Cells   |
  +------------+ span rows. | - contain |
  | body row 4 |            | - blocks. |
  +------------+------------+-----------+
  
Typical result:  

Grid table:

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

Simple table
-------------

Raw reStructuredText:
::

  Simple table:
  
  =====  =====  ======
     Inputs     Output
  ------------  ------
    A      B    A or B
  =====  =====  ======
  False  False  False
  True   False  True
  False  True   True
  True   True   True
  =====  =====  ======
  
Typical result:  

Simple table:

=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  ======

