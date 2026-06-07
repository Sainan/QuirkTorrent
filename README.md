# pluto-bittorrent

Monorepo of my BitTorrent servers, tools, and libraries written in Pluto.

## Servers

- [in-memory-tracker](in-memory-tracker.pluto) — a basic UDP tracker server
- [magnet-seeder](magnet-seeder.md) — a torrent peer that only provides metadata

## Tools

- [benc2json](benc2json.pluto) & [json2benc](json2benc.pluto) — convert between bencoding and JSON
- [dht-query](dht-query.pluto) — find peers for a given infohash in the DHT
- [maketorrent](maketorrent.pluto) — create a BitTorrent v1 torrent
- [maketorrentv2](maketorrentv2.pluto) — create a BitTorrent v2 torrent
- [settrackers](settrackers.pluto) — change the trackers in a .torrent file

## Libraries

- [bencoding](lib/bencoding.pluto)
- [bt2merkle](lib/bt2merkle.pluto)
- [trackerclient](lib/trackerclient.pluto)
