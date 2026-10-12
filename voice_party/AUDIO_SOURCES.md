# Voice Party audio sources

The level audio referenced by `voice_party/levels.json` is selected from public-domain / CC0 sources so it can be used in a commercial game without relying on MyInstants content.

## Open Game SFX Index

Repository: https://github.com/Mcamento8/open-game-sfx-index

The index identifies its audio library as `CC0-1.0` and keeps source/provenance metadata for the original Kenney and OpenGameArt packs.

Currently referenced files:

- `audio/oga-zombies/zombies/zombie-1.wav` through `zombie-24.wav`
- `audio/oga-levelup-powerup/Coin01.wav`
- `audio/oga-levelup-powerup/Downer01.wav`
- `audio/oga-levelup-powerup/FX01.wav`
- `audio/oga-levelup-powerup/Rise01.wav`
- `audio/oga-levelup-powerup/Rise02.wav`
- `audio/oga-levelup-powerup/Rise03.wav`
- `audio/oga-levelup-powerup/Rise06.wav`
- `audio/oga-levelup-powerup/Rise07.wav`
- `audio/oga-battle/battle_sound_effects/Bow.wav`
- `audio/oga-battle/battle_sound_effects/swish_2.wav`
- `audio/oga-battle/battle_sound_effects/swish_3.wav`
- `audio/oga-battle/battle_sound_effects/swish_4.wav`

## sound-cc0

Repository: https://github.com/code4fukui/sound-cc0

The repository's sound catalog marks these recordings as `CC0`.

Currently referenced files:

- `wahaha.wav` — laughter
- `cracker1.wav`
- `cracker2.wav`
- `switch1.wav`
- `bell1.wav`

## Selection rules

Sounds are chosen for short voice-mimic gameplay: laughs, growls, whooshes, rises/falls, and short percussive cues that a player can reasonably imitate with their voice or mouth. The game downloads the WAV at runtime and derives duration, pitch contour, energy/wave contour, and beats from the audio itself.

When adding new rounds, prefer HTTPS-hosted 16-bit PCM WAV files with clearly documented CC0/public-domain licensing and keep this file updated with their provenance.
