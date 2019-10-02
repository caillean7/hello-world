What does this mod do?
======================

This mods adds a new multiclass choice, Ranger / Thief to Baldur's Gate 2 on GemRB. Currently dualclassing is **not** possible (see notes in the tp2 file).

Combining the Ranger's devotion to nature with the resourcefulness and affinity for mechanical devices of the thief, the Ranger / Thief  excels in stealth and survival. While prefering any natural environment over urban settings, they can easily adapt to both. There are no racial restrictions for Ranger / Thiefs, but they must be of Neutral or Chaothic Good alignment. This is a multiclass-only combination, no dualclassing possible.

Installation
------------
Check where you installed GemRB (data) and mark it down.

Run WeiDU as (substituting with the real path; USE THE CORRECT dir for your GAME):

   weidu --search /path/to/gemrbs/datadir/unhardcoded/bg2/ ranger_thief/setup-ranger_thief.tp2


Alternatively, manually copy these files from unhardcoded/bg2:
  - avprefc.2da
  - classes.2da
  - clskills.2da
  - fistweap.2da
  - qslots.2da
  - skills.2da
... to the "override" dir in the game dir

For Linux: Run weinstall in the game directory, eg.:

    weinstall ranger_thief

Uninstallation
--------------
Rerun weidu and choose uninstall.

