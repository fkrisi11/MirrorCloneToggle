# MirrorCloneToggle
<b>Normal version:</b> Forces the mirror clone to be on when requested<br>
<b>GoGo Loco Flight Fix version:</b> Forces the mirror clone to be on when flying in any mode of GoGo Loco, or when requested
<br><br>
<h3 align="center">
 
  [Download latest version](https://github.com/fkrisi11/MirrorCloneToggle/releases/latest)
</h3>

<h2>How it works</h2>

There is a camera in the system, which when enabled, always renders the `MirrorReflection` layer to a 1x1 resolution render texture.<br>
This is enough to get VRChat to enable the local Mirror Clone.

<h2>Install guide</h2>
<b>Normal prefab</b><br>

- Drag and drop the `MirrorCloneToggle` prefab onto your avatar
- Merge the `MirrorCloneToggle_FX` FX layer with your avatar's FX layer, using [Av3Manager](https://github.com/VRLabs/Avatars-3.0-Manager)
- Merge the parameter list with your avatar's parameter list
<br>
<b>GoGo Loco Flight Fix prefab - Non-VRCF</b>

- Drag and drop the `MirrorCloneToggle` prefab onto your avatar
- Merge the `GoGoLoco Flight Fix/MirrorCloneToggle_FX (GGL Flight) [NON-VRCF]` FX layer with your avatar's FX layer, using [Av3Manager](https://github.com/VRLabs/Avatars-3.0-Manager)
Merge the parameter list with your avatar's parameter list
<br>
<b>GoGo Loco Flight Fix prefab - VRCFury</b><br>

- Drag and drop the `GoGoLoco Flight Fix/GoGoLoco Flight Fix [VRCF]` prefab onto your avatar
<br>

<h2>How to use</h2>

Use a parameter driver on a state, to change the value of `MirrorCloneToggle/Enabled`<br>
or<br>
Add `MirrorCloneToggle/Enabled` to your menu as a toggle, to toggle it manually as needed
<br><br>
<i>Note: If you want the system to be enabled by default, make sure that the `MirrorCloneToggle/Enabled` parameter is set to `true` default value in your parameter list</i><br>
<br>
<i>Note 2: If you are using any of the GoGo Loco Flight Fix versions of the FX layer, you can still set the `MirrorCloneToggle/Enabled` parameter to `true`, which will keep the Mirror Clone enabled, even when not flying with GoGo Loco</i>

<h2>Performance stats</h2>
- 1 local bool parameter (0 synced cost)<br>
- 0 material slots (1 texture that doesn't get used in any material)

<h2>Hierarchy layout</h2>
MirrorCloneToggle<br>
|-MirrorCloneCamera

<h2>Contributors</h2>

[WingmanDraws](https://www.twitch.tv/wingmandraws) for the idea<br>
[TohruTheDragon](https://github.com/fkrisi11) for finding the right settings and making the package<br>
[Buddy](https://buddyworks.wtf/) for the VRCFury GoGo Loco Flight Fix package
