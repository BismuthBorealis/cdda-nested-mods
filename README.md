# BismuthBorealis's Nested Mods Concept and Example for C:DDA

Yesterday I had an idea (and it was really easy to impliment)
what if you put a modinfo file within a subfolder of another mod?

And today I tried it out— and it worked:
 - "HigherMod" contains both the "higher entity" and "lower entity" items (have to be spawned in via debug menu)
 - "LowerMod" only contains the "lower entity" item.
The json file used for the lower entity item by each is the same file.

One final thing I have yet to test; if I added json for a new item directly to LowerMod's modinfo file, would Highermod read it, because it is json for an item, or would it ignore it, because it is part of a different mod's modinfo?

maybe in ver.2, if I ever do that, I'll test it.
