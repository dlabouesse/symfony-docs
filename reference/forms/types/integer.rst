.. index::
   single: Forms; Fields; IntegerType

IntegerType Field
=================

Renders an input "number" field. Basically, this is a text field that's
good at handling data that's in an integer form. The input ``number`` field
looks like a text box, except that - if the user's browser supports HTML5
- it will have some extra front-end functionality.

+-------------+-----------------------------------------------------------------------+
| Rendered as | ``input`` ``number`` field                                            |
+-------------+-----------------------------------------------------------------------+
| Options     | - `grouping`_                                                         |
+-------------+-----------------------------------------------------------------------+
| Overridden  | - `compound`_                                                         |
| options     |                                                                       |
+-------------+-----------------------------------------------------------------------+
| Inherited   | - `data`_                                                             |
| options     | - `disabled`_                                                         |
|             | - `empty_data`_                                                       |
|             | - `error_bubbling`_                                                   |
|             | - `error_mapping`_                                                    |
|             | - `invalid_message`_                                                  |
|             | - `invalid_message_parameters`_                                       |
|             | - `label`_                                                            |
|             | - `label_attr`_                                                       |
|             | - `label_format`_                                                     |
|             | - `mapped`_                                                           |
|             | - `required`_                                                         |
+-------------+-----------------------------------------------------------------------+
| Parent type | :doc:`FormType </reference/forms/types/form>`                         |
+-------------+-----------------------------------------------------------------------+
| Class       | :class:`Symfony\\Component\\Form\\Extension\\Core\\Type\\IntegerType` |
+-------------+-----------------------------------------------------------------------+

Field Options
-------------

.. include:: /reference/forms/types/options/grouping.rst.inc

Overridden Options
------------------

.. include:: /reference/forms/types/options/compound_type.rst.inc

Inherited Options
-----------------

These options inherit from the :doc:`FormType </reference/forms/types/form>`:

.. include:: /reference/forms/types/options/data.rst.inc

.. include:: /reference/forms/types/options/disabled.rst.inc

.. include:: /reference/forms/types/options/empty_data.rst.inc
    :end-before: DEFAULT_PLACEHOLDER

The default value is ``''`` (the empty string).

.. include:: /reference/forms/types/options/empty_data.rst.inc
    :start-after: DEFAULT_PLACEHOLDER

.. include:: /reference/forms/types/options/error_bubbling.rst.inc

.. include:: /reference/forms/types/options/error_mapping.rst.inc

.. include:: /reference/forms/types/options/invalid_message.rst.inc

.. include:: /reference/forms/types/options/invalid_message_parameters.rst.inc

.. include:: /reference/forms/types/options/label.rst.inc

.. include:: /reference/forms/types/options/label_attr.rst.inc

.. include:: /reference/forms/types/options/label_format.rst.inc

.. include:: /reference/forms/types/options/mapped.rst.inc

.. include:: /reference/forms/types/options/required.rst.inc
