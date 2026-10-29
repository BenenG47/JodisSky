# Jodi's Sky

**Day, night, rain and storms for Jodi's Office in *The Killing Antidote*, with a moon, a night sky and lamps you control from AltUI.**

A dark city under the moon, the haze thickening between the towers, the room lit only by her lamps or her screens. Or a grey afternoon, rain streaming down the windows, lightning over the towers and thunder rolling in a few seconds later. One toggle switches it, a page of sliders tunes it, and it comes back by itself every time you load the office.

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

- **Rain** (new in 3.2), by day and by night, also in the quick wheel (*Jodi's Sky › Rain*):
  - rain falling outside every window, in three layers (near, mid, far) so it has depth;
  - a grey, overcast sky: darker and foggier the heavier the rain;
  - a soft rain sound, muffled as if heard through the glass.
- **Water on the windows**: beads form, swell and dry on every pane; now and then one runs down and leaves a trail; in heavy rain a wavy water film streams down the glass, and the city behind it bends and blurs.

  ![Heavy rain at night: rain over the city, drops on the window, the moon through the haze](images/HeavyRain.png)

- **Storms**: lightning by day and by night, a bolt in the sky where you can see it from the office and the bedroom, a flash on the room and on Jodi, and thunder that arrives a few seconds later: a crack and a rolling rumble when it's close, a long low rumble when it's far. Twelve different thunders, so no two sound the same.
- **Real glass in the gym** (new in 3.3): the gym's three low windows had a self-lit pane that glowed the same by day and by night. They now get the same glass as the other windows, so they darken at night and show the rain and the drops. Always on.
- **Follow the clock** (new in 3.4): day and night switch by themselves with your PC's time, the time Jodi's clock shows, at the hours you choose. The Night toggle still works as a manual override until the next switch hour.
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

**Updating from Jodi's Sky 3.0, 3.2 or 3.3?** Just replace `JodisSky.pak`; your settings are kept. Follow the clock starts off, so nothing changes until you turn it on (coming from 3.0, the rain settings start at their defaults, Rain off).

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
| **Night sky (%)** | 0–300 (100) | brightness of the night sky, the sky light and the city haze |
| **Sky tint** | −100 blue … +100 dusk (0) | colour of the sky and the haze; the moonlight takes a little of it |
| **Moonlight** | 0–1.6 (0.8) | how strongly the moon lights the room and Jodi through the windows |
| **Moon size** | Real / Large / Huge / Giant | the size of the disc. Bigger looks dimmer: raise Moon disc a little |
| **Moon disc (%)** | 0–100 (100) | how bright the moon looks in the sky; 0 = no moon. The sky keeps its brightness |
| **Moon glow (%)** | 0–100 (100) | the halo around the moon; 0 = a crisp disc |
| **Fog (%)** | 100–500 (100) | **day and night**: how thick the haze is (only thicker than the game's, so the city never shows its edges) |
| **Fog start (m)** | 10–200 (10) | **day and night**: how far from the camera the haze begins. Around 30 m the nearby buildings clear while the far city stays hazy |
| **Rain** | on / off (off) | rain, overcast sky and rain sound, day and night (also in the quick wheel) |
| **Rain strength (%)** | 0–100 (60) | how much rain falls, and how grey, dark and foggy the sky gets |
| **Rain sound (%)** | 0–100 (70) | the rain's volume; 0 = silent |
| **Window drops** | on / off (on) | beads and trickles on the windows (with Rain on) |
| **Water film** | on / off (on) | the water film streaming down the glass, from Rain strength 75 % |
| **Lightning** | on / off (on) | lightning, the flash and thunder (with Rain on); more often in heavier rain |
| **Thunder (%)** | 0–200 (70) | thunder volume; 0 = silent flashes. Above 100 % it gets louder than the sound itself, near 200 % the closest cracks may sound a little rough |
| **Follow the clock** | on / off (off) | day and night switch by themselves with your PC's time (the time on Jodi's clock). See below |
| **Night from** | 0–23 (20) | the hour night begins |
| **Day from** | 0–23 (7) | the hour day begins |
| **Back to the defaults** | | resets every slider (the two hours too); no on / off switch changes |

The moon, lamp and sky settings act at night only; fog and rain work day and night. At their defaults, with Rain off, Day is the game's own office (the haze just starts 10 m away, so the room is never foggy).

**Follow the clock**: when you turn it on, and every time Jodi's Office loads, it's night between *Night from* and *Day from* (for example 20 → 7: night from 8 pm to 7 am) and day the rest of the time. While you play it checks the time once a minute and switches when one of the two hours comes. You can still flip Night by hand (or with the quick wheel); your choice holds until the next switch hour. With both hours the same it never switches.

---

## Good to know

- It only does something in **Jodi's Office**. Everywhere else it stays idle.
- The moon is the office's own sun, turned down and tinted. It sits where the game puts the sun.
- The glow around a bright moon partly comes from the game's bloom effect.
- Another mod that changes the office's lights at the same time will fight with it; use one at a time.
- Rain, drops and lightning cost next to nothing: nothing runs between strikes, and with Rain off nothing extra is drawn at all.
- The rain and thunder sounds are made by the mod's own scripts (no recordings), so they are free to share.

---

## Credits

- **BenenG47**: the mod.
- **Zyiakk**: [AltUI](https://github.com/Zyiakk/AltUI), whose Mods tab and quick wheel give Jodi's Sky its page, and the name.
- **The Blueprint Loader's author**: [Blueprint Loader](https://www.nexusmods.com/thekillingantidote/mods/994).

![A red moon over the city](images/redmoon.png)
