^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package hazard_status_converter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.39.0 (2024-11-25)
-------------------
* fix: fix ticket links to point to https://github.com/autowarefoundation/autoware.universe (`#9304 <https://github.com/youtalk/autoware.universe/issues/9304>`_)
* fix: fix ticket links to point to https://github.com/autowarefoundation/autoware.universe (`#9304 <https://github.com/youtalk/autoware.universe/issues/9304>`_)
* chore(package.xml): bump version to 0.38.0 (`#9266 <https://github.com/youtalk/autoware.universe/issues/9266>`_) (`#9284 <https://github.com/youtalk/autoware.universe/issues/9284>`_)
  * unify package.xml version to 0.37.0
  * remove system_monitor/CHANGELOG.rst
  * add changelog
  * 0.38.0
  ---------
* Contributors: Esteve Fernandez, Yutaka Kondo

0.38.0 (2024-11-08)
-------------------
* unify package.xml version to 0.37.0
* feat!: replace autoware_auto_msgs with autoware_msgs for system modules (`#7249 <https://github.com/autowarefoundation/autoware.universe/issues/7249>`_)
  Co-authored-by: Cynthia Liu <cynthia.liu@autocore.ai>
  Co-authored-by: NorahXiong <norah.xiong@autocore.ai>
  Co-authored-by: beginningfan <beginning.fan@autocore.ai>
* feat: remake diagnostic graph packages (`#6715 <https://github.com/autowarefoundation/autoware.universe/issues/6715>`_)
* fix(hazard_status_converter): check current operation mode (`#6733 <https://github.com/autowarefoundation/autoware.universe/issues/6733>`_)
  * fix: hazard status converter
  * fix: topic name and modes
  * fix check target mode
  * fix message type
  * Revert "fix check target mode"
  This reverts commit 8b190b7b99490503a52b155cad9f593c1c97e553.
  ---------
* Contributors: Ryohsuke Mitsudome, Takagi, Isamu, Yutaka Kondo

0.26.0 (2024-04-03)
-------------------
* feat(tier4_system_launch): add option to launch mrm handler (`#6660 <https://github.com/autowarefoundation/autoware.universe/issues/6660>`_)
* feat(hazard_status_converter): add package (`#6428 <https://github.com/autowarefoundation/autoware.universe/issues/6428>`_)
* Contributors: Takagi, Isamu
