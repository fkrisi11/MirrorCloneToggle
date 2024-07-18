# MirrorCloneToggle
 Forces the mirror clone to be on when requested
<br><br>
<h3 align="center">
 
  [Download latest version](https://github.com/fkrisi11/MirrorCloneToggle/releases/latest)
</h3>

<h2>How it works</h2>
There is a camera in the system, which when enabled, always renders the "MirrorReflection" layer to a 1x1 resolution render texture.<br>
This is enough to get VRChat to enable the local Mirror Clone.

<h2>Install guide</h2>
<ul>
 <li>Drag and drop the prefab onto your avatar</li>
 <li>Merge the FX layer with your avatar's FX layer, using Av3Manager</li>
 <li>Merge the parameter list with your parameter list</li>
</ul>

<h2>How to use</h2>
Use a parameter drive on a state, to change the value of "MirrorCloneToggle/Enabled"<br>
or<br>
Add "MirrorCloneToggle/Enabled" to your menu as a toggle, to toggle it manually as needed
<br><br>
<i>Note: If you want the system to be enabled by default, make sure that the "MirrorCloneToggle/Enabled" parameter is set to "true" default value in your parameter list</i>

<h2>Performance stats</h2>
- 1 local bool parameter (0 synced cost)<br>
- 0 materials (1 texture that doesn't get used)

<h2>Hierarchy layout</h2>
MirrorCloneToggle<br>
|-MirrorCloneCamera

<h2>Contributors</h2>

[WingmanDraws](https://www.twitch.tv/wingmandraws) for the idea<br>
[TohruTheDragon](https://github.com/fkrisi11) for finding the right settings and making the package
