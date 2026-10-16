# Recorded sound credits — v0.7.2

The following source packs identify their audio as **CC0 / public domain**. Downloaded originals and captured source pages are retained outside the release in `../audio_sources/`. Processed game clips are in `assets/audio/recorded/`.

| Source | Creator | Use in this game |
| --- | --- | --- |
| [The Free Firearm Sound Library](https://opengameart.org/content/the-free-firearm-sound-library) | Ben Jaszczak, Brian Nelson, Kevin Heras, Matthew Nanney | Recorded pistol, rifle, shotgun, AK, carbine, SMG and marksman shots. Shortened tails, mono conversion, high-pass filtering and peak normalization. Two recordings per weapon family. Minigun/turret reuse the AK recordings at their actual firing cadence. |
| [Helicopter Sounds](https://opengameart.org/content/helicopter-sounds) | aquinn | Recorded rotor loop, trimmed and crossfaded. Shared by all seven helicopters with distance attenuation. |
| [Racing car engine sound loops](https://opengameart.org/content/racing-car-engine-sound-loops) | domasx2 | Engine loop with a crossfaded seam. Source author confirmed replacement with a public-domain sample in the July 24, 2011 comment. |
| [Gun Reload Sound Effects](https://opengameart.org/content/gun-reload-sound-effects) | BMacZero / Brian MacIntosh | Recorded magazine and action sounds, trimmed and normalized; synchronized with existing magazine removal, insertion and slap events. |
| [Footsteps](https://opengameart.org/content/footsteps-0) | GboxMikeFozzy | Six recorded footsteps, normalized, randomized and timed to player movement. These are general footsteps, not a surface-specific simulation. |
| [Explosions](https://opengameart.org/content/explosions-4) | EZduzziteh | Designed explosion sound for robot/vehicle destruction and the missile impact layer. |
| [Muffled Distant Explosion](https://opengameart.org/content/muffled-distant-explosion) | NenadSimic | Recorded low log-drum boom with natural reflections, layered with the missile impact. This is a cinematic effect, not a recording of a real nuclear blast. |

Gun voices have small pitch variations; automatic fire preserves overlapping tails. Playback is capped at eight local and 24 spatial one-shot voices. Vehicles use separate distance-attenuated loops. Separate Weapons, Vehicles, Foley and World buses feed a master limiter. Existing healing gulps and incoming missile whistle remain synthesized.

The anatomical hand source and existing visual asset licenses remain as documented with the project's assets. This update uses the existing hand geometry for driving grips and does not replace the restored operator meshes.

## v0.8.0 original sounds

`motorbike.wav` is an original synthesized engine loop authored for this project. The motorbike combines low-frequency combustion pulses and exhaust noise; RPM changes during play. These are not recordings of a specific Honda model. All previously listed recording licenses remain unchanged.

## v0.8.7 stock human pain/death reactions

Four stock recordings from **Mixkit / Envato**, downloaded October 14, 2026:

| Game file | Stock title / item ID | Source page |
| --- | --- | --- |
| death_voice_0.wav | Man in pain — 2197 | https://mixkit.co/free-sound-effects/hurt/ |
| death_voice_1.wav | Human fighter pain scream — 2768 | https://mixkit.co/free-sound-effects/fight/ |
| death_voice_2.wav | Battle man scream — 2175 | https://mixkit.co/free-sound-effects/fight/ |
| death_voice_3.wav | Fighting man's voice — 2171 | https://mixkit.co/free-sound-effects/fight/ |

License: [Mixkit Sound Effects Free License](https://mixkit.co/license/#sfxFree). The license explicitly permits commercial and non-commercial video games and modification/incorporation into larger end products. These recordings are NOT CC0. Do not redistribute them as standalone stock or in source-file asset packs; the release embeds them in the playable game. Individual performer names are not listed on the source cards.

Converted to mono 44.1 kHz 16-bit PCM, high-pass filtered at 65 Hz, trimmed with breath/tail padding, peak-balanced and edge-faded. No pitch shifting, artificial growls or added reverb. Original downloads and a processing manifest remain locally in `../audio_sources/mixkit_pain/`, outside the release archive. The old HaelDB voice bank is retired and no longer shipped.

Human NPC deaths have a 48% voice chance, increased to 72% for fatal vehicle impacts. Four takes shuffle without immediate repeats; modest volume variation, spatial distance attenuation, at most three concurrent voices, and 0.8–1.25 seconds between cues. Robot deaths retain mechanical effects. Voices stop on returning to the main menu.

## v0.8.9 robot chest beam

`assets/audio/recorded/robot_beam.wav` is an original short synthesized electrical effect created for this project (frequency sweep, harmonics and a brief noise transient). No external recording or voice sample is used.

## Original melee Foley (v0.9.3)

`knife_swing_0/1/2.wav` and `knife_impact.wav`: original synthesized, band-shaped noise swishes and a short damped impact, generated for this project. No third-party recording.

## Core overload warning (v0.9.4)

`core_warning.wav` is an original synthesized warning chirp. Blast layers reuse the previously credited explosion/distant-boom recordings.
