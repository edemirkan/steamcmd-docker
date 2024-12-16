# SteamCMD-Docker

SteamCMD is a command-line version of the Steam Client. Its primary use is to install and update various dedicated servers available on Steam.
This container was made to be used as a base image for building out other game specific containers but can be used for any other tasks SteamCMD can perform.

For more detailed information about using SteamCMD see the official [wiki](https://developer.valvesoftware.com/wiki/SteamCMD).

## Usage

### Pull latest image
```shell
docker pull ghcr.io/edemirkan/steamcmd:latest
```
### Download Garrysmod
```shell
docker run -it ghcr.io/edemirkan/steamcmd:latest +login anonymous +app_update 4020 +quit
```
