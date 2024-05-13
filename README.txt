This is a fork of Josh771's HDFX, so all credits go to him.
For the most part, this fork focuses on making HDFX more optimised by reworking some parts of the system, and also adding some QoL here and there.

NOTE: Gibbing has been disabled until I can find a better way to handle it (that and i also don't really like gibbing lol)

Changes:
- Added an options menu for all CVars
- Dust now uses VisualThinkers instead of Actor (should be faster)
	- originally, dust used a very simplified version of Actor's Tick, so why not just use a VisualThinker instead and rewrite part of the Tick override
- Blood splats now combine together if stacking on top of another blood splat (the new one gets destroyed, and the old one gets its lifetime renewed)
- Gibbing is disabled for the reasons mentioned in the note above
