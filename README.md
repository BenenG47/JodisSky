# Jodi's Sky

**Day and night for Jodi's Office in *The Killing Antidote*, with a moon, a night sky and lamps you control from AltUI.**

A dark city under the moon, the haze thickening between the towers, the room lit only by her lamps or her screens. One toggle switches it, a page of sliders tunes it, and it comes back by itself every time you load the office.

![Jodi at the window under a black night sky](images/01.png)

---

## Features

- **Night in one click**: AltUI's Mods tab, or the quick wheel (*Jodi's Sky › Night*). Day puts the office back exactly as the game made it.
- **A real night, not a filter**: the office's own lights are changed live. The sun becomes a moon, the sky and the city haze go dark blue, and the room really gets dark.
- **The moon**: its light on the room and on Jodi, the disc in the sky, its size (Real / Large / Huge / Giant) and its glow, each on its own slider.
- **Your lamps**: from full light to 0 %, where only the moon and the screens light the room. Made for movie nights with [DesktopTV](https://github.com/BenenG47/DesktopTV-v1).

  ![Jodi's Sky at night with DesktopTV](images/JodisSky.gif)

- **Wardrobe-friendly**: night doesn't mean dressing in the dark. Keep the lamps bright enough and the wardrobe stays comfortable to use, while the city outside stays at night.

  ![The wardrobe at night with the lamps up](images/wardrobe.png)

- **Sky colour**: from a cold blue night to a red dusk.
- **Fog, day and night**: thicker haze over the city, and how far from the window it starts. Jodi's room itself never gets foggy.

  ![Thicker haze over the city](images/fog.png)

- **Remembered**: every setting is saved and applied by itself about a second after Jodi's Office loads.
- **Light**: a plain pak. No UE4SS, no game files replaced, nothing running outside Jodi's Office. Works on Linux (Steam / Proton) too.

---

## Requirements

1. **[Blueprint Loader](https://www.nexusmods.com/thekillingantidote/mods/994)**: starts the mod in the game.
2. **[AltUI](https://www.nexusmods.com/thekillingantidote/mods/988)**: the settings page and the quick-wheel toggle.
   Without AltUI the mod still applies your last saved settings; you just can't change them.

No UE4SS needed.

---

## Installation

Copy `JodisSky.pak` into the game's `TheKillingAntidote\Mods\` folder (the game must be closed).

**Updating from OfficeNight?** Jodi's Sky is OfficeNight renamed. Delete `OfficeNight.pak` from `Mods\` (and turn off the old UE4SS *OfficeNight* script if you had it), or they will fight over the same lights. Settings start fresh under the new name.

**Uninstall**: delete `JodisSky.pak`. Its settings live in `%LOCALAPPDATA%\TheKillingAntidote\Saved\SaveGames\JodisSky.sav` and can be deleted too.

---

## Settings

AltUI › **Mods** › **Jodi's Sky**. Every change applies at once (sliders while you drag).

| Setting | Range (default) | What it does |
|---|---|---|
| **Now** | | Day or Night, or "Not in Jodi's Office" |
| **Night** | on / off | switches day and night (also in the quick wheel) |
| **Room lamps (%)** | 0–100 (100) | the office's lamps at night. 20 = a dim room, 0 = only the moon and the screens |
| **Moonlight** | 0–1.6 (0.8) | how strongly the moon lights the room and Jodi through the windows |
| **Moon disc (%)** | 0–100 (100) | how bright the moon looks in the sky; 0 = no moon. The sky keeps its brightness |
| **Moon size** | Real / Large / Huge / Giant | the size of the disc. Bigger looks dimmer: raise Moon disc a little |
| **Moon glow (%)** | 0–100 (100) | the halo around the moon; 0 = a crisp disc |
| **Night sky (%)** | 0–300 (100) | brightness of the night sky, the sky light and the city haze |
| **Sky tint** | −100 blue … +100 dusk (0) | colour of the sky and the haze; the moonlight takes a little of it |
| **Fog (%)** | 100–500 (100) | **day and night**: how thick the haze is (only thicker than the game's, so the city never shows its edges) |
| **Fog start (m)** | 10–200 (10) | **day and night**: how far from the camera the haze begins. Around 30 m the nearby buildings clear while the far city stays hazy |
| **Back to the defaults** | | resets everything except Night |

Everything acts at night only, except the two fog settings. At their defaults, Day is the game's own office (the haze just starts 10 m away, so the room is never foggy).

---

## Good to know

- It only does something in **Jodi's Office**. Everywhere else it stays idle.
- The moon is the office's own sun, turned down and tinted. It sits where the game puts the sun.
- The glow around a bright moon partly comes from the game's bloom effect.
- Another mod that changes the office's lights at the same time will fight with it; use one at a time.

---

## Credits

- **BenenG47**: the mod.
- **Zyiakk**: [AltUI](https://github.com/Zyiakk/AltUI), whose Mods tab and quick wheel give Jodi's Sky its page, and the name.
- **The Blueprint Loader's author**: [Blueprint Loader](https://www.nexusmods.com/thekillingantidote/mods/994).

![A red moon over the city](images/redmoon.png)
