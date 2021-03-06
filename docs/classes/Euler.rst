Euler
#####

The ``Euler`` class template represents an euler angle rotation/orientation,
with predefined typedefs of type ``float`` and ``double``.

The ``Euler`` class is derived from ``Imath::Vec3`` and thus has
fields named ``x``, ``y``, and ``z``, which correspond to the first,
second, and third rotation angles in a specified order, which,
depending on the order, may not correspond directly to x, y, or z
rotations.

Example:

.. literalinclude:: ../examples/Euler.cpp
   :language: c++

.. doxygentypedef:: Eulerf

.. doxygentypedef:: Eulerd

.. doxygenclass:: Imath::Euler
   :undoc-members:
   :members:


   
