^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cob_gazebo_objects
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.6.7 (2016-10-24)
------------------

0.6.6 (2016-10-10)
------------------
* Moved ipa-office walls to cob gazebo worlds
* Set correct origin/scale for ipa-office_walls and added walls for stairway
* Updated model of ipa-office_walls
* Added object for ipa-office walls
* Merged branch 'feature/ipa_production_plant_improvement' and updated the structure.
* working on meshes
* Added additional files for outsourced content
* Changes made based on PR review by fxm
* added files to spawn storage racks - note: spawning is not working yet
* Contributors: Florian Weisshardt, ipa-fxm, ipa-mig-mc, ipa-srd-rd

0.6.5 (2016-04-01)
------------------
* add launch file
* add urdf and stl
* add ikea kallax mesh
* fix man urdfs
* fix meshes
* old objects deleted
* added people, move.py and changed model names
* added people and the possibility to move objects
* Contributors: Florian Weisshardt, hannes, ipa-fxm

0.6.4 (2015-08-29)
------------------
* migration to package format 2
* remove trailing whitespaces
* remove obsolete autogenerated mainpage.dox files
* review dependencies
* Contributors: ipa-fxm

0.6.3 (2015-06-17)
------------------
* beautify CMakeLists
* Contributors: ipa-fxm

0.6.2 (2014-12-15)
------------------

0.6.1 (2014-09-22)
------------------

0.6.0 (2014-09-18)
------------------
* Merge pull request `#65 <https://github.com/ipa320/cob_simulation/issues/65>`_ from ipa320/hydro_dev
  bringin updates from hydro_dev
* Merge pull request `#64 <https://github.com/ipa320/cob_simulation/issues/64>`_ from ipa320/hydro_release_candidate
  Hydro release candidate
* 0.5.2
* update changelog
* Contributors: Florian Weisshardt

0.5.2 (2014-08-28)
------------------
* cleaning up
* New maintainer
* Contributors: ipa-fxm, ipa-nhg

0.5.1 (2014-03-21)
------------------
* changes for textures
* fix test for ikea table
* cb_9x6 fixed
* Created specific empty world for ipa environments
* Changed name medication_prospan to medicine_prospan and moved the default camera position
* Created new objects
* Addapted .dae files for new gazebo version
* Initial catkinization without rostest stuff
* move object locations to cob_default_env_config
* remove qr code
* update objects for apartment, .model files not working yet
* tomato_soup now uses mesh in collision tag
* New format for object_locations, it is necessary define the parameter model name
* New format for object_locations, it is necessary define the parameter model name
* Updated mass value for milk model
* Updated mass value for milk model
* Added elevators in ipa-apartment world
* changed file permissions
* Moved load parameters for objects in simulation to cob_gazebo_objects
* update deps
* add urdf tests for world and objects
* new ipa-apartment environment
* New ipa-apartment environment
* Moved couch from cob_gazebo_worlds to cob_gazebo_objects
* new ipa-apartment environment
* Renamed objects
* Rename objects
* Salt and tomaten sauce models
* move chair
* Move spanw_object.py to cob_bringup_sim
* Fixed depend mistake and renamed objects
* New urdf models of the objects
* New urdf object models
* deleted launch files for objects
* New origins for the models
* Modifications in spawn_object.py, now support urdf.xacro files and rpy parameters
* New script spawn_object.py and config files
* new packege cob_gazebo_objects
* Contributors: Jannik Abbenseth, abubeck, ipa-fmw, ipa-fxm, ipa-nhg
