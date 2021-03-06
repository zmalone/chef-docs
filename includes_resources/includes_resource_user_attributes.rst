.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

This resource has the following attributes:

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Attribute
     - Description
   * - ``comment``
     - |comment user|
   * - ``force``
     - |force_remove_user|

       .. warning:: Using this attribute may leave the system in an inconsistent state. For example, a user account will be removed even if the user is logged in. A user's home directory will be removed, even if that directory is shared by multiple users.
   * - ``gid``
     - |id group|
   * - ``home``
     - |home_directory|
   * - ``iterations``
     - |mac os x| platform only, 10.8 (or higher). |iterations|
   * - ``manage_home``
     - |user homedir|

       |user homedir_create|

       |user homedir_modify|
   * - ``non_unique``
     - |non_unique_user|
   * - ``password``
     - |password shadow_hash|
   * - ``provider``
     - Optional. |provider resource_parameter| |see providers|
   * - ``salt``
     - |mac os x| platform only, 10.7 or higher. |salt| |mac os x| version 10.7 uses SALTED-SHA512 and version 10.8 (and higher) uses SALTED-SHA512-PBKDF2 to calculate password shadow hashes. 
   * - ``shell``
     - |shell|
   * - ``supports``
     - |supports user| Default value: ``:manage_home => false, :non_unique => false``.
   * - ``system``
     - |system user|
   * - ``uid``
     - |user uid|
   * - ``username``
     - |name user| Default value: the ``name`` of the resource block. |see syntax|