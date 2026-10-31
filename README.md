# Sandala Arena

A blocky 3D arena game in one web page: up to 10 players throw slippers, charge
power throws, build with blocks, chat and send emojis. No accounts needed.

**Play:** https://ask220119.github.io/timo-arena-sandala/

## How online play works

Players' browsers connect directly to each other (WebRTC, through the
[Trystero](https://github.com/dmotz/trystero) library). Public Nostr relays are
only used to introduce players; game data goes straight between players. There
is no server and nothing to pay for. A few strict networks (some school or
mobile-data networks) block direct connections; those players play alone with bots.

Scores are remembered on each device under the player's name.

## Controls

- Keyboard: `W A S D` move, mouse or arrows look, `Space` jump, click to throw,
  hold click for a POWER throw, `B` build mode, `1`–`6` emojis, `T` chat.
- Tablet/phone: left stick moves, drag to look, on-screen buttons for the rest.

Taym, the owner, enters with his password and throws two slippers at once.
