# Owlbear Tracks for blendOS

These are my personal Tracks for blendOS. The name is taking advantage of the fact that blendOS calls their system configuration file (system.yaml) subtypes "tracks", which makes it more fun for me at least.

These are all based on my personal configuration, and are here mostly to facilitate a reinstall because I'm an incurable distrohopper who insists on trying things on bare metal. If you also find them useful, neat!

For now, this also includes the basic tracks from the original blendOS repo that I'm keeping for reference, minus the ones I just ain't gonna use. The originals here are:

* **blendOS Base**: blendos-base
	* The base track others are based on. I'm going to use this as 				a basis for Owlbear-Core
* **Gnome**: `gnome`
	* The base Gnome track, which I will be modifying to make Gnomeish-Owlbear

And that's it for now. I might add an XFCE one or a more customized one if I get ambitious. Maybe a Gamer-Owlbear or what have you.

## Owlbear's Custom Tracks

These are the ones I'm building for myself, because blendOS's system.yaml thing is kinda fun, and I want  to learn more. 

* **Owlbear Core**: `owlbear-core`
	* The baseline that the other stuff is built off of, a modified version of blendos-base, but with zsh as the default shell. I also stripped out AMD support since this is for my laptop, which is an intel. I'll add in an AMD-Owlbear version eventually.
* **Gnomeish Owlbear**: `gnomish-owlbear`
    + My very vanilla Gnome setup. This leaves out some stuff and adds in some other stuff, but is a pure gnome build with only Gnome and Gnome Circle apps included and no pre-installed Extensions!

## To Do

[X] Update Readme

[X] Copy blendos-base.yaml and gnome.yaml, rename to owlbear-core and gnomish-owlbear, and change iml in each

[X] Delete KDE, Cinnamon, LXQT, Mate

[X] Modify owlbear-core and test

[X] modify gnomish-owlbear and test

[X] remove blendos-base and gnome

[] create versions of owlbear-core for AMD procs (currently intel-only)

[] other fun stuff

[] Backup my current system.yaml
