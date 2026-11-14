# **2027.2.0**

## New
* Added **Space Walk** to tilt and turn your playspace in every direction, like floating in space.
* Added **Show Loading-bar on Startup** in **Settings > General > Window Behavior**. Turn it off to see the interface faster.

## Changes
* VRC+ decorations in lists and on your own profile card now only animate while you hover over them.
* Removed the **Optimize VRC+ Usage** setting since it is now always on.

## Linux
* **OSC Tool** now works on Linux.
* **Media Relay** now works on Linux.
* **Discord Presence** now works on Linux.
* **Space Flight** and **Space Turn** now work on Linux.
* **Avatar Scaling** now works on Linux.
* **YouTube Fix** now works on Linux through Steam and has its own Linux guide.
* **Efficiency Mode** now works on Linux.
* You can now start VRChat in VR or desktop mode from VRCNext on Linux.
* Desktop notifications now work on Linux and show VRCNext images.
* Added a tray icon on Linux with your profile and a status menu.
* The **Custom Chatbox** can now show the song that is playing on Linux.
* The **Custom Chatbox** can now show the active window on Linux with X11, and VRCNext can install the needed tools for you.
* Improved the Linux installer.
* Fixed memory growing on Linux while blurred effects are on screen.
Commits by @hollyntt

## Performance
* Groups open about twice as fast.
* Profiles load faster.
* The **Timeline** and the activity in profiles load faster, especially with a long history.
* VRCNext no longer freezes while **Kikitan XD** or **Voice Fight** start or stop.
* VRCNext no longer freezes while VR tools connect and SteamVR is still starting.
* The VRChat log viewer uses much less memory with large log files.
* Slightly faster startup with less memory used.
* Much lower CPU and GPU usage while VRCNext is open and idle.
* VRChat data now loads faster because responses are downloaded compressed.
* Switching tabs is faster.
* The crash watchdog uses much less memory.
* Less memory is used for players you have met.
* Less background work for your friends list, mutual friends and the activity log.
* The interface loads faster at startup.
* VRCNext logs you in faster at startup.
* Less CPU usage on Linux while a lot of data arrives at once.
* On Linux with NVIDIA graphics, VRCNext no longer starts a second copy of itself in the background.

## Fixes
* Fixed images not being cached after logging in again inside the app.
* Fixed notifications showing up again in the timeline, as VR alerts and as sounds after opening the notification list.
* Fixed closed instances staying in **My Instances** until the next refresh.
* Fixed **Status Schedule** not restoring your previous status after you saved or toggled a rule while it was active.
* Fixed memory usage growing the longer VRCNext stays open.
* Fixed the group owner name sometimes going missing.
* Added missing css for the new instance badges and vibes.
* Fixed the Linux setting **Enable Hardware Acceleration** doing nothing. It is now called **Force Software Rendering**.
* Fixed VRCNext passing software rendering settings to Steam and other programs it opens on Linux.
* Fixed VRCNext crashing right after start on PCs without .NET 10.