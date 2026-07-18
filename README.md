# IRONCLAD

A fantasy 2D side-scrolling beat 'em up. You play a knight; you defeat the knights who come at you.

In the lineage of **Golden Axe**, **Knights of the Round**, and **Streets of Rage 4**. Block is the identity — time your guard, punish the swing. Knight-vs-knight is the point: fights are about reading and spacing, not enemy gimmick soup.

## Play

Open `index.html` in a browser, or serve it:

```
python -m http.server 5783
```

Then visit http://localhost:5783.

## Controls

| Key | Action |
|-----|--------|
| Arrows / WASD | Move (left/right + depth) |
| J | Light attack (chains into a 3-hit combo) |
| K | Heavy attack |
| L / Space | Block (hold) |
| R | Reset |

## Status — v1 complete ✅

- **M0 — Core feel** — knight vs. grunt, four verbs, hitstop, health bars, death
- **M1 — Combat depth** — parry→stagger→punish, grab beats block, defensive grunt (the attack/block/grab triangle)
- **M2 — Enemy roster** — grunt / berserker / spearman / shieldbreaker / captain, each punishes a different bad habit; multi-enemy engine
- **M3 — Stage & progression** — scrolling world, screen-lock waves, boss, 1-of-3 upgrade picks, lives/continues, win state
- **M4 — The Knights-of-the-Round look** — shaded paper-doll rig, parallax backdrop (moon/towers/torches), arcade HUD, vignette
- **M5 — Shell & ship** — title/pause/settings menus, rebindable keys, SFX+music, localStorage + hi-score, procedural WebAudio

Single-file HTML + Canvas 2D. Debug hook at `window.__ironclad`.
