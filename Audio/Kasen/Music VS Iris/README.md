couple notes regarding the song:
- i haven't tested the song on any of the default voicegroups so you may want to save yourself the hassle and use the one provided here.
- there are times where the song uses 6 instruments at a time even though emerald by default only supports 5. you'll need to either increase the limit by editing "SOUND_MODE_MAXCHN_SHIFT" (increases IWRAM usage) or simply edit the midi and remove the piano track (it's the least significant track as it's really only used for an echo effect here and there)