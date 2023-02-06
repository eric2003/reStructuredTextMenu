Linenothreshold
=========================
  
Raw reStructuredText:
::

  .. highlight:: python
     :linenothreshold: 5
  
  ::
   
     for letter in 'Python':
        print("haha") 
  
Typical result:  

.. highlight:: python
   :linenothreshold: 5

::
 
   for letter in 'Python':
      print("haha") 

Raw reStructuredText:
::

  .. highlight:: python
     :linenothreshold: 5
  
  ::
  
     for letter in 'Python':
        print("haha1")
        print("haha2")
        print("haha3")
        print("haha4")
  
  
Typical result:  

.. highlight:: python
   :linenothreshold: 5

::

   for letter in 'Python':
      print("haha1")
      print("haha2")
      print("haha3")
      print("haha4")
