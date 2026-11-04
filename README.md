# autoupdatewindstock

Release host for the Windstock launcher's downloadable servers. The full launcher reads
`servers.json` from the latest release and downloads the Windstock 0.35 and 0.71 server
packs listed in it. Not meant to be used by hand.

## Layout

Each release holds `servers.json` (versions and SHA-256 of every pack) and one
`windstock-server-<id>.zip` per game: `035` (Pokémon GO 0.35) and `071` (0.71).
Built by `tools/make_server_packs.sh` in the Windstock launcher project.
