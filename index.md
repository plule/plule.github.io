My projects include work around math art, experimental video games and boring tooling.

This is a list of some of them.

## dfhack-remote

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

## bevy-collapsor

[bevy-collapsor](https://github.com/plule/bevy-collapsor) is a quick and dirty rust program based on the [bevy engine](https://bevyengine.org/) generating terrains. It works [in a browser.](https://plule.github.io/bevy-collapsor/)

## MPCIC

[MPCIC](https://github.com/plule/MPCIC) is a C# commandline tool for creating instruments usable in the recent MPC drum machines.

## DEFract

[DEFract](https://github.com/plule/DEFract) is a lua program based on [LÖVE](https://love2d.org/) drawing 3d fractals.

![Rotated Mandelbox](http://i.imgur.com/Vshm6.jpg)

## Jam games

These games were done with limited time, a long time ago.

- [A New World](https://github.com/plule/A-New-World): Psychedelism and recursivity in an office.
- [Run and Escape](https://github.com/plule/LD48-24): Some run and jump game?
- [1GAM-February](https://github.com/plule/1GAM-February): The one time I wrote javascript

