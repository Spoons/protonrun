# protonrun
protonrun is a simple script which allows one to run games, or other applications, in GloriousEggroll's Proton distribution directly from the CLI. protonrun will download and update GE-Proton for you.

## Getting Started
By default, protonrun's files, which include your game saves, and end up in HOME/proton. To change this behavior, define PROTON\_PATH in your environment. 

1. `protonrun install`
2. `protonrun run [SteamAppId] [Binary Path]`

## Useage
```
Usage: 
  protonrun [-h|--help]
  protonrun install
  protonrun run [SteamAppId] [Path]

Proton exec wrapper
  -h, --help	Prints help
  install	installs GE proton and creates prefix
  run		executes binary at PATH with fixes from SteamAppId

Assign PROTON_PATH to change prefix and proton location.
```
