# magnet-seeder

A minimal BitTorrent v1 server/peer to help resolve metadata from magnet: URIs.

## Why?

So web-seeded torrents can benefit from the convenience of magnets.

## How?

You can append `&x.pe=<peer-address>` to a magnet link to "initiate a direct metadata transfer between two clients while reducing the need for external peer sources" as per [BEP 9](https://www.bittorrent.org/beps/bep_0009.html).
