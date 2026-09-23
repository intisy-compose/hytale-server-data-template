Default data for the `hytale` slot of
[game-compose](https://github.com/intisy-compose/game-compose), so a fresh
`git clone --recursive` runs out of the box. It holds no server files yet: the server image
generates its defaults on first start, and runtime state (worlds, saves, logs) is gitignored.

## Use your own data

Fork or replace this repo and commit your configuration (the dedicated server's configuration files), then point the slot at it
from the game-compose checkout:

```powershell
.\docker-compose.ps1 data use hytale <owner/repo[@ref]>   # your own data repo, optionally a branch
.\docker-compose.ps1 data use hytale                      # back to this template
```

Commit configuration, not runtime state.
