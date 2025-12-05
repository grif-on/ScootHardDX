# This is a community-maintained fork of ScootHardDX.

This fork is not affiliated with, endorsed by, or associated with SanyaWaffles and Waffle Iron Studios.

SanyaWaffles explains reasons behind deletion of original repository and binary downloads in the [blogpost](https://waffleironstudios.com/posts/2024-10-15-Mothballing%20Scoot%20Hard%20DX%20and%20Daytime%20Drama.html) .

This fork preserves the historical beloved pony Doom mod under the terms of the initial BSD 3-Clause License.

# Origin of commit history

Most of the git history is restored thanks to [marius851000 fork](https://github.com/marius851000/ScootHardDX).
- These commits are done by SanyaWaffles under BSD 3-Clause License.

While a small number of the commits (between 1.2 and 1.3 versions) are restored from unpacking "sharddx.ipk3" file which was freely available and had BSD 3-Clause License file inside of it (MD5 of "sharddx.ipk3" file - `8c440d70aa2b50eeccd401c6058e4fcc` | SHA256 "sharddx.ipk3" of file - `a0cb6336810f9e42f2de4b016a0900cebbc8cc049727efbec8ed9951aebf355c`).
- These commits are marked with `(restored from sharddx.ipk3)` in git history.

# How to play:

1. Compress the contents of this repository into "scoot_hard_dx.ipk3" file.
	- You can do so with this 7-zip console command `7z a -r -mx9 -tzip "-xr!.git" scoot_hard_dx.ipk3 .\*`
2. Run it with [UZDoom](https://zdoom.org/downloads) . This mod DOES NOT require Doom's iwads (i.e. you don't need paid Doom assets)!
	- You can take different approaches to run "scoot_hard_dx.ipk3" file:
		- Place it near "uzdoom.exe" and simply run "uzdoom.exe" like any other program. After that select "Scoot Hard DX" in uzdoom's "game file to run" GUI.
		- Supply it as command line argument for "uzdoom.exe" like this - `"absolute_path_to\uzdoom.exe" -IWAD "absolute_path_to\scoot_hard_dx.ipk3"`. In such a way you can create desktop shortcut for quick launch.
		- Place it inside folder in which your mod manager automatically searches for iwads. For example, for [DoomModLoader](https://www.moddb.com/mods/doom-mod-loader) it is a ".\FILE\IWAD\" folder (same goes for uzdoom files, place them inside ".\FILE\PORT\UZDoom\"). After that, starting the game via DoomModLoader GUI should be straightforward.
3. If you have visual or fps problems - try to switch Rendering API in settings and restart the game (Vulkan and OpenGL seem to work fine).

# Contributing

Since this is a community-maintained fork, feel free to open PRs and issues. Be sure you are fine to contribute under BSD 3-Clause License.

Don't ask for a new content though. This is a preservation project after all.
