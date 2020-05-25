# Making Mods
## Injecting Mods
Beat Saber _**does not**_ have built in mod support.

Instead, most mods within the mod installer rely on [BSIPA (Beat Saber Illusion Plugin Architecture)](https://github.com/nike4613/BeatSaber-IPA-Reloaded/) to inject plugins into the game, as well as providing some useful tools for us modders.

Previously, we used [IPA (Illusion Plugin Architecture)](https://github.com/Eusth/IPA). Some plugins still use this, and is temporarily supported by BSIPA. We still use IPA for the mod tutorial, however it is recommended to use BSIPA for any future modding endeavors.

::: warning 
## BSIPA DMCA
Recently (May 20th, 2020), BSIPA was hit with a [DMCA takedown](https://github.com/github/dmca/blob/master/2020/05/2020-05-20-beatsaber.md), along with other repositorys. In the mean time, you can download the latest version of BSIPA (4.0.5) from [Beatmods.com](https://beatmods.com/#/mods) or directly, [here](https://beatmods.com/uploads/5e89a8e603dce96ca6cf0eb5/universal/BSIPA-4.0.5.zip).

As far as source code for BSIPA goes, someone who has the latest source code, should replace this block of text with a link to the source code.
:::



For those of you who prefer [BepInEx](https://github.com/BepInEx/BepInEx) over either of these options, Bepis is supposedly working on a BSIPA emulator for BepInEx, and already has one available for regular IPA plugins. As for developing Beat Saber plugins for BepInEx, well, you're kinda on your own.

## Project Setup
If you are interested in creating a Beat Saber mod, but do not have a template or Visual Studio template set up, [follow the Intro guide to get your project all set up](./intro.md).

### Ready to go?
Check out the [links below](#other-links) for documentation relating to Unity and related tooling. If you have any questions, the best place to ask is in the `#pc-mod-dev` channel on the [BSMG Discord](https://discord.gg/beatsabermods)

## Launch args
Helpful launch arguments that will make modding / debugging easier.

| Argument&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description |
| - | :- |
| `--verbose`  | Enables the output log window for IPA. This will show the debug console that mods use.  |
| `fpfc` | "First Person Flying Controller"<br /><br />This allows you to use WASD and the mouse to navigate around the menu in game. This makes testing much easier, because you don't have to put on your headset! |
| `-vrmode oculus` | If you are running Beat Saber through Steam, this allows you to play the game on an Oculus headset. |

## Other Links
* [BeatMods](https://beatmods.com)
* [BeatMods Approval Guidelines](https://docs.google.com/document/d/15RBVesZdS-U94AvesJ2DJqcnAtgh9E2PZOcbjrQle5Y/edit?usp=sharing)
* [Unity Scripting API](https://docs.unity3d.com/ScriptReference/index.html)
* [dnSpy](https://github.com/0xd4d/dnSpy)
* [Harmony](https://github.com/pardeike/Harmony)
* [Beat Saber IPA](https://github.com/nike4613/BeatSaber-IPA-Reloaded)
