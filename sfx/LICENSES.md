# Sound licences (public/sfx)

These are the only sounds the game plays. `src/audio.ts` maps game sound keys to these files. None of them come from
Trap Master.

Sources:
- **Epic Toon FX** (Archanor VFX, Unity Asset Store, https://assetstore.unity.com/packages/vfx/particles/epic-toon-fx-57772),
  bought by the user, v1.8, Unity Asset Store EULA (Standard Unity Asset Store EULA, single entity licence). Files `etfx_*.wav`
  from Assets/Epic Toon FX/Sound, trimmed, level-matched and encoded to mono 96 kbps MP3. Installed 2026-11-20 at the user's
  request; they replace the earlier Kenney/in-house versions of the same keys.
- **Kenney**: audio packs by Kenney (www.kenney.nl), **CC0 1.0** (public domain,
  http://creativecommons.org/publicdomain/zero/1.0/). Free for commercial use, credit optional.
  The packs used, from their official pages on kenney.nl/assets:
  - Impact Sounds: https://kenney.nl/assets/impact-sounds
  - Interface Sounds: https://kenney.nl/assets/interface-sounds
  - Digital Audio: https://kenney.nl/assets/digital-audio
  - Casino Audio: https://kenney.nl/assets/casino-audio
  - Music Jingles: https://kenney.nl/assets/music-jingles
  - RPG Audio: https://kenney.nl/assets/rpg-audio
  - Sci-Fi Sounds: https://kenney.nl/assets/sci-fi-sounds
- **In-house**: synthesized by us with numpy (sine/noise synthesis, Karplus-Strong plucks). We own these outright.

Kenney sources were trimmed, layered, re-pitched and level-matched. Every file was then encoded to mono 96 kbps MP3
(the music is stereo 112 kbps).

| File | Plays on | Source | Licence |
|---|---|---|---|
| music_loop.mp3 | background music (32 s loop, 120 BPM, plus 0.1 s of wrap padding at each end) | in-house composition and synthesis | own |
| ui_pop.mp3 | button click | Epic Toon FX `etfx_shoot_bubble.wav` | Unity Asset Store EULA |
| ui_tab.mp3 | home tab switch | Epic Toon FX `etfx_shoot_snowball.wav` | Unity Asset Store EULA |
| ui_buy.mp3 | shop upgrade bought | Epic Toon FX `etfx_explosion_magic.wav` | Unity Asset Store EULA |
| ui_coins.mp3 | gold claimed (goals, mystery box) | Epic Toon FX `etfx_explosion_minimagic2.wav` | Unity Asset Store EULA |
| win.mp3 | stage complete panel | Kenney Music Jingles `jingles_STEEL10` | CC0 |
| pusher_add.mp3 | ADD pusher bought | Epic Toon FX `etfx_explosion_poof.wav` | Unity Asset Store EULA |
| speed_up.mp3 | SPEED bought | Epic Toon FX `etfx_explosion_lightning.wav` | Unity Asset Store EULA |
| squish_1/2/3.mp3 | stickman knocked out (random of 3) | Epic Toon FX `etfx_explosion_slime2.wav` / `etfx_explosion_liquid3.wav` / `etfx_shoot_bubble2.wav` | Unity Asset Store EULA |
| lava_plop.mp3 | knocked stickman lands in the lava / water | Epic Toon FX `etfx_explosion_lava.wav` | Unity Asset Store EULA |
| box_appear.mp3 | mystery box appears | Epic Toon FX `etfx_spawn.wav` | Unity Asset Store EULA |
| box_hit.mp3 | mystery box tapped | Epic Toon FX `etfx_explosion_sharp.wav` | Unity Asset Store EULA |
| box_open.mp3 | mystery box opens | Epic Toon FX `etfx_explosion_magic2.wav` | Unity Asset Store EULA |
| hit_punch.mp3 | strike: glove, monkey punch, zombie hand | Epic Toon FX `etfx_target_hit.wav` | Unity Asset Store EULA |
| hit_wood.mp3 | strike: hammer, log, totem | Epic Toon FX `etfx_explosion_sharp.wav` | Unity Asset Store EULA |
| hit_plank.mp3 | strike: ship wheel, barrel, barrier | Epic Toon FX `etfx_explosion_dark02.wav` | Unity Asset Store EULA |
| hit_cannon.mp3 | strike: cannon | Epic Toon FX `etfx_explosion_rocket2.wav` | Unity Asset Store EULA |
| hit_boom.mp3 | strike: pumpkin bomb, meteor | Epic Toon FX `etfx_explosion_grenade.wav` | Unity Asset Store EULA |
| hit_rock.mp3 | strike: boulder, temple stone ball, spiked ball | Epic Toon FX `etfx_explosion_dark01.wav` | Unity Asset Store EULA |
| hit_metal.mp3 | strike: anchor, crane hook, snowplow | Epic Toon FX `etfx_impact_metal03.wav` | Unity Asset Store EULA |
| hit_clang.mp3 | strike: wrecking ball, bulldozer | Epic Toon FX `etfx_impact_metal01.wav` | Unity Asset Store EULA |
| hit_clank.mp3 | strike: robot arm, magnet, piston, gear, space arm | Epic Toon FX `etfx_impact_metal02.wav` | Unity Asset Store EULA |
| hit_swoosh.mp3 | strike: mast boom, scythe | Epic Toon FX `etfx_shoot_storm.wav` | Unity Asset Store EULA |
| hit_whip.mp3 | strike: vine whip | Epic Toon FX `etfx_shoot_flash.wav` | Unity Asset Store EULA |
| hit_splat.mp3 | strike: frog tongue, cream blast | Epic Toon FX `etfx_explosion_slime.wav` | Unity Asset Store EULA |
| hit_boing.mp3 | strike: bamboo spring | Epic Toon FX `etfx_explosion_bubble.wav` | Unity Asset Store EULA |
| hit_bonk.mp3 | strike: coconut, penguin | Epic Toon FX `etfx_stun01.wav` | Unity Asset Store EULA |
| hit_candy.mp3 | strike: lollipop, candy cane | Epic Toon FX `etfx_explosion_sparkle3.wav` | Unity Asset Store EULA |
| hit_pop.mp3 | strike: gumball cannon | Epic Toon FX `etfx_pop_balloon.wav` | Unity Asset Store EULA |
| hit_snow.mp3 | strike: snowball | Epic Toon FX `etfx_explosion_snow.wav` | Unity Asset Store EULA |
| hit_ice.mp3 | strike: ice spinner | Epic Toon FX `etfx_explosion_frost.wav` | Unity Asset Store EULA |
| hit_air.mp3 | strike: airlock blast | Epic Toon FX `etfx_shoot_gas.wav` | Unity Asset Store EULA |
| hit_zap.mp3 | strike: gravity pad | Epic Toon FX `etfx_shoot_lightning.wav` | Unity Asset Store EULA |
| ab_arrows.mp3 | ability: Arrow Rain | Epic Toon FX `etfx_shoot_pistol01.wav` | Unity Asset Store EULA |
| ab_whirlwind.mp3 | ability: Whirlwind | Epic Toon FX `etfx_explosion_storm.wav` | Unity Asset Store EULA |
| ab_swift.mp3 | ability: Swift Enemies | Epic Toon FX `etfx_shoot_energy02.wav` | Unity Asset Store EULA |
| ab_acid.mp3 | ability: Acid Bath | Epic Toon FX `etfx_explosion_acid.wav` | Unity Asset Store EULA |
| ab_overload.mp3 | ability: Trap Overload | Epic Toon FX `etfx_shoot_lightning2.wav` | Unity Asset Store EULA |
| ab_clone.mp3 | ability: Enemy Cloner | Epic Toon FX `etfx_explosion_mystic02.wav` | Unity Asset Store EULA |
| ab_airstrike.mp3 | ability: Air Strike (whistle) | Epic Toon FX `etfx_explosion_nuke.wav` | Unity Asset Store EULA |
| ab_blackhole.mp3 | ability: Black Hole | Epic Toon FX `etfx_explosion_soul.wav` | Unity Asset Store EULA |
| ab_golden.mp3 | ability: Golden Touch | Epic Toon FX `etfx_explosion_sparkle2.wav` | Unity Asset Store EULA |
