This project alters the Nymashock core for Bizhawk to improve how Castlevania SotN (Usa) performs. It reduces
slowdown, shortens load times, and expands available system memory from 2MB to 8MB. For use with BizHawk
versions 2.8, 2.9.1, or 2.10. Intended for use with the Randomizer ( sotn.io )

Instructions:
First make a copy of your Bizhawk Folder as the new core should only run Castlevania SotN and not other PS1 games.
Running other games might be possible but is not recommended. 

shock.wbx.gz and shock.wbx.zst are replacement Nymashock core files. You must rename or remove your original file
which will be in your Bizhawk\DLL folder. BizHawk 2.8 uses shock.wbx.gz, newer versions use shock.wbx.zst

Then place the new shock.wbx core file in the DLL folder.

Core Changes by SonicDreamcaster & MottZilla

* RAM Expansion (for future mods)
* CD Load Speed Increase
* Timing changes (to reduce or eliminate slowdowns)

------------------

You can see the source changes online here: 

https://github.com/sonicdcer/BizHawk/commit/3d1743173881cfe5cfbe47ad8db1d22f5f38b917
https://github.com/sonicdcer/mednafen/commit/9feffcd550a1aaa6fc7fd6f5e9de8edd164e6b13

You can build the waterbox Nymashock core yourself or use the included shock.wbx
built by SonicDreamcaster.

You can also browse the included source files. The included files are the only ones changed
from BizHawk 2.9.1's source tree. 
