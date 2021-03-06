.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

This resource has the following attributes:

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Attribute
     - Description
   * - ``atomic_update``
     - |atomic_update| Default value: ``true``.
   * - ``backup``
     - |backups_kept| Default value: ``5``.
   * - ``cookbook``
     - |cookbook file_location| The default value is the current cookbook.
   * - ``force_unlink``
     - |force_unlink| Default value: ``false``.
   * - ``group``
     - |windows group_identifier|
   * - ``helper``
     - |helper| Default value: ``{}``.
   * - ``helpers``
     - |helpers| Default value: ``[]``.
   * - ``inherits``
     - |windows| only. |inherits windows security| Default value: ``true``.
   * - ``local``
     - |local_template| Default value: ``false``.
   * - ``manage_symlink_source``
     - |manage_symlink_source| Possible values: ``nil``, ``true``, or ``false``. When this value is set to ``nil``, the |chef client| will manage a symlink's source file and emit a warning. When this value is set to ``true``, the |chef client| will manage a symlink's source file and not emit a warning. Default value: ``nil``. The default value will be changed to ``false`` in a future version.
   * - ``mode``
     - |mode resource_file|
       
       The behavior is different depending on the platform.
       
       |unix|- and |linux|-based systems: |mode *nix|
       
       |windows|: |mode windows security|
   * - ``owner``
     - |owner windows security|	
   * - ``path``
     - |path full_path_to_file|

       |windows|: A path that begins with a forward slash (``/``) will point to the root of the current working directory of the |chef client| process. This path can vary from system to system. Therefore, using a path that begins with a forward slash (``/``) is not recommended.
   * - ``provider``
     - Optional. |provider resource_parameter| |see providers|
   * - ``rights``
     - |windows| only. |rights windows security|
   * - ``sensitive``
     - |sensitive| Default value: ``false``.
   * - ``source``
     - |source template| |source template_cookbook| |source template_local| This attribute may also be used to distribute specific files to specific platforms. |see file_specificity| Default value: the ``name`` of the resource block. |see syntax|
   * - ``variables``
     - |variables passed_to_template|
       
       .. include:: ../../includes_template/includes_template_partials_variables_attribute.rst
