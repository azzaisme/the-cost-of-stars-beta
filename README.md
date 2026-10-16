# The Cost of Stars: beta

An arena roguelite about what it takes to hold the line.

You fly out of a forward station, through four zones of the belt, toward a
hostile Gate past Jupiter. Every flight is a different pilot. What you carry
only counts if you get it home, and the pilots who don't come home go on a wall
with their names on it. Nothing here is free.

These are beta builds, straight from development: expect rough edges, and
expect each one to change things.

## Play it

**[The latest build](https://github.com/azzaisme/the-cost-of-stars-beta/releases/latest)**,
or [every build so far](https://github.com/azzaisme/the-cost-of-stars-beta/releases).
Each release says what changed in it.

| for | file | what to do with it |
|---|---|---|
| Steam Deck and Linux | `TheCostOfStars-<version>-linux-x86_64.tar.gz` | Unpack it and run `TheCostOfStars.x86_64`, with anything that came with it beside it. On a Steam Deck, add it to Steam as a non-Steam game in Desktop Mode, then play it from Game Mode with the controller layout on Gamepad. |
| Windows | `TheCostOfStars-<version>-windows-x86_64.zip` | Unzip it and run `TheCostOfStars.exe`, with `TheCostOfStars.pck` and anything else that came with it beside it. It isn't code signed yet, so SmartScreen warns the first time: **More info**, then **Run anyway**. |
| A browser | `TheCostOfStars-<version>-web.zip` | Unzip it and serve the folder over http(s), for example `python3 -m http.server` inside it. Opened as a file, it won't start. |
| Android (arm64) | `TheCostOfStars-<version>-android-arm64.apk` | Sideload it. It plays with touch, or with a controller or keyboard plugged in. If a new one won't install over the old, uninstall the old one first. |

Each build is about a gigabyte, most of it the bosses' effects. It's built for
the Steam Deck: 1280×800 and a controller first, though a keyboard and mouse
work everywhere.

## Updating

You don't need to download the whole game again for each build. The title
screen says which version you're playing, and when there's a newer one it
offers **UPDATE TO** it: usually a few megabytes rather than a gigabyte.
Press it, then **RESTART INTO** it (on Android, close the game and open it
again).

Now and then a build is a full one, and the title says so and opens its page:
that one is the whole download, and the updates after it start from it. Each
release's notes say which kind it is. The `.update.zip` files and
`update.json` on a release are what the game downloads; nobody needs to open
them. The web build is always the whole game, served fresh.

## About this repository

It holds the builds and nothing else. Each one is published here
automatically when a version of the game is released.
