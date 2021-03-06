.. THIS PAGE DOCUMENTS chef-client version 11.6

=====================================================
apt_package
=====================================================

.. include:: ../../includes_resources_common/includes_resources_common_generic.rst

.. include:: ../../includes_resources/includes_resource_package_apt.rst

.. note:: |note resource_based_on_package|

Syntax
=====================================================
.. include:: ../../includes_resources/includes_resource_package_apt_syntax.rst

Actions
=====================================================
.. include:: ../../includes_resources/includes_resource_package_apt_actions.rst

Attributes
=====================================================
.. include:: ../../includes_resources/includes_resource_package_apt_attributes.rst

Providers
=====================================================
.. include:: ../../includes_resources_common/includes_resources_common_provider.rst

.. include:: ../../includes_resources_common/includes_resources_common_provider_attributes.rst

.. include:: ../../includes_resources/includes_resource_package_apt_providers.rst

Examples
=====================================================
|generic resource statement|

**Install a package using package manager** 

.. include:: ../../step_resource/step_resource_apt_package_install_package.rst

**Install a package using local file** 

.. include:: ../../step_resource/step_resource_apt_package_install_package_using_local_file.rst

**Install without using recommend packages as a dependency**

.. include:: ../../step_resource/step_resource_apt_package_install_without_recommends_suggests.rst