.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

This lightweight resource provider has the following attributes:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Attribute
     - Description
   * - ``application_provider``
     - 
   * - ``create_dirs_before_symlink``
     - |create_dirs_before_symlink lwrp application|
   * - ``deploy_key``
     - |deploy_key lwrp application|
   * - ``enable_submodules``
     - |git| only. |enable_submodules lwrp application|
   * - ``environment``
     - |environment variable_hash|
   * - ``environment_name``
     - |name environment|
   * - ``force``
     - 
   * - ``group``
     - |group lwrp application|
   * - ``migrate``
     - |migrate lwrp application|
   * - ``migration_command``
     - |migration_command lwrp application|
   * - ``name``
     - |name application|
   * - ``owner``
     - |owner lwrp application|
   * - ``packages``
     - |packages lwrp application|
   * - ``path``
     - |password application|
   * - ``purge_before_symlink``
     - |purge_before_symlink lwrp application|
   * - ``repository``
     - |repository lwrp application|
   * - ``restart_command``
     - |restart shell_command| Default value: ``nil``.
   * - ``revision``
     - |revision| Default value: ``HEAD``.
   * - ``rollback_on_error``
     - |rollback_on_error lwrp application|
   * - ``scm_provider``
     - |name scm_provider|
   * - ``strategy``
     - |strategy lwrp application|
   * - ``symlink_before_migrate``
     - |symlink_before_migrate lwrp application|
   * - ``symlinks``
     - |symlinks lwrp application|
