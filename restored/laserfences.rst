.. index:: Laser Fences

============
Laser Fences
============

Laser Fences used to work in Red Alert 2 and Yuri's Revenge 1.000 but
stopped working with the arrival of the 1.001 patch, in that the
'lasers' never turned on (this appears to have been an incidental
change and not something Westwood did intentionally).

Laser Fences now work just the same as they did in Tiberian Sun. You
need a BuildingType with ``LaserFencePost=yes`` to act as a corner post,
and another BuildingType with ``LaserFence=yes`` which will be placed in
between the corner posts automatically (see the original building's
SHP from Tiberian Sun to see how the art is controlled). These fences
are impassable to ground objects and invulnerable to normal damage,
but when a corner post is destroyed, the fences connected to it are
lost. When the corner post loses power, the fences connected to it go
offline and become freely passable. When the post regains power, the
fences reactivate and any object unfortunate enough to be traversing
them will be destroyed. Laser Fences LaserFence= LaserFencePost=

.. versionadded:: 0.1

