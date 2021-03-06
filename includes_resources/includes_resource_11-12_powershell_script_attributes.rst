.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

This resource has the following attributes:

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Attribute
     - Description
   * - ``architecture``
     - |architecture windows_process| |architecture windows_process_i386| Possible values: ``:i386`` (for 32-bit processes) and ``:x86_64`` (for 64-bit processes).
   * - ``code``
     - |code quoted_string|
   * - ``command``
     - |name command| Default value: the ``name`` of the resource block. |see syntax|
   * - ``flags``
     - |flags powershell_script| Default value: ``-NoLogo, -NonInteractive, -NoProfile, -ExecutionPolicy RemoteSigned, -InputFormat None, -File``.
   * - ``interpreter``
     - |interpreter| The default interpreter is ``Cmd.exe``. To ensure that |windows powershell| is the interpreter, use the ``guard_interpreter`` common attribute with a value of ``:powershell_script``.
   * - ``provider``
     - Optional. |provider resource_parameter| |see providers|

