GH3+
====

GH3+ is a work in progress plugin system for Guitar Hero III written in C++.

This branch provides strumless mode for use with other instruments and controllers. Only the 5 fret keys are now needed to play the game.

Compile with "C:\Program Files (x86)\MSBuild\14.0\Bin\msbuild.exe" "G:\Projects\GH3-Plus-master\src\plugins\taphopochord\taphopochord.vcxproj" /p:Configuration=Release

Move core.dll, taphopochord.dll, forcetapnotes.dll to PLUGINS
Also notelimitfix.dll, tiltfix.dll, whammyfix.dll

All these need to be compiled with same syntax as above. Install visual studio 2015 full and set VCTargetsPath env variable to C:\Program Files (x86)\MSBuild\Microsoft.Cpp\v4.0\V140

Remove all existing plugins and compile new plugins as needed. Do not mix plugins compiled on different environments!


Latest release
--------------

The most recent release is v0.6. This release contains:
- core
- AlwaysDoubleNotes
- ForceStrumNotes
- ForceTapNotes
- GemShuffle
- Speedhack
- MirrorMode
- NoteLimitFix
- TapHopoChord
- TextureHelper
- TiltFix
- WhammyFix

Fixes from the latest version include:
- Major updates to the GH3+ API include support for most of GH3's native "Qb" structures/classes.
- Open notes
