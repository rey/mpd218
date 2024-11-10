# Akai MPD218 setup

## MPD218 Editor

1. Download [MPD218 Editor](https://www.akaipro.com/downloads.html#mpd218)
2. Open the `reyrey.mpd218` preset (this is identical to `Preset1-chroma10.mpd218` in the [MPD218 Factory Presets](https://cdn.inmusicbrands.com/akai/MPD218-FactoryPresets.zip)).
3. `File` → `Send To Hardware`
4. `Save current preset to hardware as 1`
5. Click `Send`
6. Hopefully you'll never have to change the preset again(!)

## MPC2

1. Download [MPC2](https://www.akaipro.com/mpc-software-2)
2. Open the `Midi Learn` pane (`shift` + `command` + `L`)
3. Click on the weird burger menu → `Import`

### If using MPC2 by itself

1. Import the `mpd218-mpc2.xmm` MIDI mapping
2. Under the `User` dropdown, select `mpd218-mpc2`

### If using MPC2 as a VST plugin in Ableton

1. Import the `mpd218-mpc2-ableton.xmm` MIDI mapping
2. Under the `User` dropdown, select `mpd218-mpc2-ableton`

### 2024-11 Update!

I've found the import functionality a bit ropy. You might want to do the following instead:

#### If using MPC2 by itself

Drop `mpd218-mpc2.xmm` into `~/Library/Application Support/Akai/MPC/Midi Learn` and restart MPC2.

#### If using MPC2 as a VST plugin in Ableton

Drop `mpd218-mpc2-ableton.xmm` into `~/Library/Application Support/Akai/MPC/Midi Learn` and restart MPC2.
