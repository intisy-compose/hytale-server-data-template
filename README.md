# Hytale server data (template)

Public **template** data repo for [game-compose](https://github.com/intisy-compose/game-compose).
It is the default mounted into the `hytale-server-data-template` slot so a fresh clone runs out of the box.

Placeholder for Hytale server configuration. Populate once the dedicated server is available.

## Use your own data

Fork or replace this repo, then point the slot at it:

```bash
./data.sh use hytale-server <owner/repo[@ref]>   # from the game-compose repo
```

Worlds, saves and logs are gitignored — commit configuration, not runtime state.

## License

MIT
