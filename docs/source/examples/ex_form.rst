..
  NOTE: This RST file was generated by `make examples`.
  Do not edit it directly.
  See docs/source/examples/example_doc_generator.py

Form Example
===============================================================================

An example of the ``Form`` widget.

A ``Form`` is a simple subclass of ``Container`` which automatically lays
out it children in two columns, neatly aligning the widget edges. If
a ``Form`` has an odd number of children, the last child will span both
columns. The typical use case of a ``Form`` alternates ``Label`` and ``Field``
instances, but there is not restriction on the types of children used
with a form, except that they be constrainable.

.. TIP:: To see this example in action, download it from
 :download:`form <../../../examples/widgets/form.enaml>`
 and run::

   $ enaml-run form.enaml


Screenshot
-------------------------------------------------------------------------------

.. image:: images/ex_form.png

Example Enaml Code
-------------------------------------------------------------------------------
.. literalinclude:: ../../../examples/widgets/form.enaml
    :language: enaml
