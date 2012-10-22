A collection of Lua scripts/APIs and schematics for creating advanced machines in Tekkit (Minecraft)

This was all created using Tekkit 3.1.2

# Scripts

## nuke-controller
Fully automatic Nuclear Reactor Power Plant, using ComputerCraft control system.

Handles monitoring, fueling and cooling of one or more nuclear reactors.

### Schematics

See `nuke-schema.png`

**NOTE:** This is only compatible with IC2 version 1.103, but a reconfiguration would make it compatible with latest revisions (There has been some changes to the cooling procedures).

### Console Usage

Run `nuke-controller [(-debugOn true|false), (-dryRun true|false)]`

Copy `nuke-controller.startup` to `/disk/startup` to automatically start (and update to latest version) on boot/server-restart (assuming HTTP is enabled)

### Instructions

* Build according to schematics and correctly configure parameters and peripherals
* Start the Application (described above)
* Click the connected button (ONCE) to start up reactors and initialize systems
- The core should now be running
* Click the connected button (ONCE -- again) to perform the shutdown procedure

The alarm will sound when first powering up the reactor and when the thermostat is triggered.

Default configuration is set to 10 Cooling-cells, 44 Fuel-cells and a maximum core-temp at 2000 degrees.
This outputs ~1800 EU per reactor.

### Screenshots

![Power Plant Screenshot](https://raw.github.com/andersevenrud/TekkitScripts/master/nuke-controller-screens/2012-09-27_02.17.04.png)

![Power Plant Console Screenshot](https://raw.github.com/andersevenrud/TekkitScripts/master/nuke-controller-screens/2012-09-26_22.22.08.png)

### Videos and Demonstrations

![Video Preview](https://raw.github.com/andersevenrud/TekkitScripts/master/nuke-controller-screens/animation.gif)

Full video can be viewed on my [YouTube Channel video](http://www.youtube.com/watch?v=MTzRL2bmeRo "Direct link to video")

## nuke-stats
Display stats from `nuke-controller`

### Console Usage

Run `nuke-stats` (Remember to check configuration parameters in the top section of script)

Copy `nuke-stats.startup` to `/disk/startup` to automatically start (and update to latest version) on boot/server-restart (assuming HTTP is enabled)

### Screenshots

![Power Plant Status Display Screenshot](https://raw.github.com/andersevenrud/TekkitScripts/master/nuke-stats-screens/2012-09-26_22.26.13.png)

### Videos and Demonstration

Included in the video from nuke-controller section above. [This link skips directly to the status demonstration](http://youtu.be/MTzRL2bmeRo?t=2m13s "Direct link to video")

## dl-script
Download a file from pastebin.com and save it on the console or disk.

### Console Usage

Run `dl-script <url> <absolute-destination-path>`, launch without arguments to see more

# Licence

See the [LICENCE file](https://github.com/andersevenrud/TekkitScripts/blob/master/LICENCE "LICENCE Document")

# Links

* Code and Schematics: https://github.com/andersevenrud/TekkitScripts
* Blog post on `nuke-controller` and `nuke-stats`: http://anderse.wordpress.com/2012/09/29/fully-automatic-nuclear-power-plant-in-tekkit-minecraft/
* YouTube Videos: http://www.youtube.com/playlist?list=PLzC5Z5D-YLyEY0JCxCfb7LrzofYyJtJlO
