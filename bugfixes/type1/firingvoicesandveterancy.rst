.. index:: Veterancy; Units won't lose their special weapon firing voices once they become elite.

===========================
Firing Voices and Veterancy
===========================
Yuri's Revenge uses different unit voice lists for firing weapons (
``VoicePrimaryWeaponAttack``, ``VoicePrimaryEliteWeaponAttack``,
``VoiceSecondaryWeaponAttack`` and ``VoiceSecondaryEliteWeaponAttack``).
If the ``*EliteWeaponAttack`` list is empty, ``VoiceAttack`` is used
instead of the more appropriate non-elite version ``*WeaponAttack``.
This behavior makes units like Boris, Magnetrons, Siege Choppers,
Boomers and Floating Discs lose their special voices once they become
elite. Ares falls back to the non-elite weapon firing voices instead
of using the generic ``VoiceAttack`` ones.

.. versionadded:: 0.2
  