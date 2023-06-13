# reshade-linux
Bash script to download ReShade and the shaders and link them to games running with wine or proton on Linux.  

## Usage

### Quick:
Download the script:

    curl -LO https://github.com/matsilagi/reshade-steam-proton/raw/main/reshade-linux.sh
Make it executable:

    chmod u+x reshade-linux.sh
Execute the script:

    ./reshade-linux.sh

### Detailed:
For detailed usage, follow the instructions in the script's source:

https://github.com/matsilagi/reshade-steam-proton/blob/main/reshade-linux.sh#L21

## Alternatives

### vkBasalt:
https://github.com/DadSchoorse/vkBasalt

For native Linux Vulkan games, Windows games which can run through DXVK (D3D9 / D3D10 / D3D11) and Windows games which can run through VKD3D (D3D12).

### vkBasalt through Gamescope:

Since [gamescope](https://github.com/Plagman/gamescope/) can use Vulkan, you can run vkBasalt on gamescope itself, instead of on the game.

## Misc
`reshade-linux.sh` is a newer script which works with any Windows game running under wine or proton.  
`reshade-linux-slim.sh` is the same as above, but only downloads the "Slim" repository for a light installation.
`reshade-linux-flatpak.sh` is a script which executes `reshade-linux.sh` with the correct path for Steam installed from Flatpak.  
`reshade-linux-flatpak-slim.sh` is the same as above, but executes `reshade-linux-slim.sh` instead for the light installation.
`reshade-steam-proton.sh` (obsolete - will be removed eventually) is a older script which relies on protontricks / only works with Steam.
