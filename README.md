An open source cheat for Counter-Strike: Global Offensive on Linux.

## Current Features

 - Basic GDB injector
 - ImGui menu
 - Chams
 - ESP
 - Weapon ESP
 - Chicken/Fish ESP
 - World colour modulation
 - Force square radar
 - Recoil crosshair
 - Rank revealer
 - Radio fake ban/fake chat
 - Clantag (and pBeeMovie clantag)
 - Backtracking
 - Backtrack Chams
 - Flappy Bird clone
 - Legitbot
 - Hitmarkers
 - Nightmode
 - Skybox changer
 - Skinchanger
 - Ragebot (currently in development and doesnt have awall so no mindmg/hitchance/autoshoot)
 - AntiAim (currently sways, need to fix lby breaker)
 - Movement cheats (Jumpbug, humanoid bhop, edgebug, etc.)

## How to use

### Debian / Ubuntu / Pop OS / Linux Mint required packages:

`sudo apt install -y libsdl2-dev cmake git gcc-10 g++-10 gdb clang`

### Arch / Manjaro required packages:

`sudo pacman -S --needed base-devel git cmake gdb sdl2 git clang`

### Fedora required packages:

`sudo dnf install gcc-g++ gdb SDL2-devel cmake git clang`

### OpenSUSE required packages:

`sudo zypper install gcc gdb SDL2-devel cmake git llvm-clang llvm-gold`

```sh
git clone https://github.com/SmurfsCC/CheatCSGO
cd x352
chmod +x toolbox.sh
./toolbox.sh -p -u -b -l # pull, unload cheat if currently injected, build and then load, use -h for help
```


## Basic toolbox.sh usage

| Argument           | Description                             |
| ------------------ | --------------------------------------- |
| -u (--unload)      | Unload the cheat from CS:GO if loaded   |
| -l (--load)        | Load/inject the cheat via gdb           |
| -ld (--load_debug) | Load/inject the cheat and debug via gdb |
| -b (--build)       | Build to the build/ dir                 |
| -bd (--build_debug)| Build to the build/ dir as debug        |
| -p (--pull)        | Update the cheat                        |
| -h (--help)        | Show help                               |

All args are executed in the order they are written in, for example, "-u -b -l" would unload the cheat, build it, and then load it back into csgo.
