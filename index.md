## Current projects

These are the software and libraries done recently.

### Vox Uristi

[Vox Uristi](https://plule.github.io/vox-uristi) is a tool to export maps from the game Dwarf Fortress to a voxel format and make
pretty pictures.

![capture](https://plule.github.io/vox-uristi/assets/arelumid.jpg)

### Theremotion

[Theremotion](https://plule.github.io/theremotion/) is a synthesizer inspired by the Theremin. You play it with gestures in the air.

{% include youtube.html id="GGALeKm_uzc" %}

### MPC Valet

[MPC Valet](https://plule.github.io/mpc_valet/) is an online tool to create sample based instruments to use on MPC drum machines.

![capture](https://raw.githubusercontent.com/plule/mpc_valet/main/assets/capture.png)

### dfhack-remote

[dfhack-remote](https://github.com/plule/dfhack-remote) is a rust library to talk to the [Dwarf Fortress](http://www.bay12games.com/dwarves/) video game remotely.

```rust
let mut client = dfhack_remote::connect().unwrap();
let world_map = client.remote_fortress_reader.get_world_map().unwrap();
println!(
    "Welcome to {} ({}). It is the year {}.",
    world_map.get_name(),
    world_map.get_name_english(),
    world_map.get_cur_year(),
);
```

### bevy-collapsor

[bevy-collapsor](https://github.com/plule/bevy-collapsor) is a quick and dirty rust program based on the [bevy engine](https://bevyengine.org/) generating terrains. It works [in a browser.](https://plule.github.io/bevy-collapsor/)

## Old Projects

These projects are very old and unmaintained, but can still be of interest.

### DEFract

[DEFract](https://github.com/plule/DEFract) is a lua program based on [LÖVE](https://love2d.org/) drawing 3d fractals.

![Rotated Mandelbox](http://i.imgur.com/Vshm6.jpg)

### MPCIC

[MPCIC](https://github.com/plule/MPCIC) is a C# commandline tool for creating instruments usable in the recent MPC drum machines. I've since made MPC Valet with the same features but in the browser.

### Jam games

These games were done with limited time, a long time ago.

- [A New World](https://github.com/plule/A-New-World): Psychedelism and recursivity in an office.
- [Run and Escape](https://github.com/plule/LD48-24): Some run and jump game?
- [1GAM-February](https://github.com/plule/1GAM-February): The one time I wrote javascript
