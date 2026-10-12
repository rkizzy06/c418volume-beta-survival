# C418 Volume Beta Only

A Minecraft resource pack that limits survival music to tracks from C418's *Minecraft – Volume Beta*.

Every song is already in the base game. This pack only changes when they play. No audio files are included.

## What plays where

**Overworld** (all biomes, caves and underwater):
Biome Fest, Blind Spots, Haunt Muskie, Aria Math, Dreiton, Taswell, Mutation, Moog City 2, Beginning 2, Floating Trees, plus the disc tracks Blocks, Chirp, Far, Mall, Mellohi, Stal, Strad, Ward and Wait (at reduced volume).

**Nether** (all biomes):
Concrete Halls, Dead Voxel, Warmth, Ballad of the Cats.

**The End, dragon fight, credits:** unchanged. Vanilla already plays The End, Boss and Alpha.

## Unchanged

- Title screen music
- Jukeboxes
- Creative-only tracks still play in creative

## Notes

- Ki, Flake, Kyoto and Intro aren't in Minecraft, so they can't be included.
- Eleven is left out on purpose.
- To hear it right away, set **Music Frequency** to **Constant** in Music & Sounds settings (if your version has it).

## Compatibility

Works on Minecraft Java 1.20.3 and newer. Earlier versions use different music file names and won't play anything.

## Install

1. Download `Volume_Beta_Survival.zip` from the [Releases](../../releases) page.
2. Put it in your `.minecraft/resourcepacks` folder.
3. In Minecraft, open Options → Resource Packs and move it to Selected.

To build the zip yourself, zip `pack.mcmeta` and the `assets` folder together. They must sit at the top level of the zip, not inside another folder.

## Files

- `pack.mcmeta`: pack name and supported versions
- `assets/minecraft/sounds.json`: remaps each survival music event to Volume Beta tracks
- `assets/minecraft/lang/en_us.json`: display names for disc tracks in the "now playing" popup

## Credits

All music by C418. This project is not affiliated with or endorsed by C418, Mojang or Microsoft.

## License

[MIT](LICENSE)
