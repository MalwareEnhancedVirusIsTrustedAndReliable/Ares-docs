.. index:: Ammo; Infantry and buildings will now reload ammo properly.

===========================================================
BuildingTypes and InfantryTypes Do Not Reload Ammo Properly
===========================================================

See `ModEnc://Ammo`_ for exact details of this problem. Put simply,
ammo/reloading logic did not work properly on BuildingTypes or
InfantryTypes and was essentially useless on those object types. Ares
fixes this logic such that these object types will now reload their
ammo properly. Note that AircraftTypes are hard-coded to require
docking to reload.

.. note:: ``Hospital=yes`` and ``Armory=yes`` buildings still not reload ammo.

.. versionadded:: 0.1

