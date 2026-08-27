# Supra-Organism — lab talk

A self-contained HTML slide deck on the sound work for **Supra-Organism**
(Grisha Coleman, MIT Future Fest, Little Kresge, 3 October 2026) — the FlowEdit
breath→instrument morphing and The Concatenator song-rebuilt-from-breath strands,
plus the studio rig they run on.

Open `index.html` in any browser. No build step, no server, works offline.

| key | |
|---|---|
| ← → | previous / next slide |
| N | speaker notes |
| P | print (→ PDF) |
| Home / End | first / last slide |

Slide 15 carries a stepped **morph ladder** — eleven discrete positions along one
FlowEdit trajectory (source → nine intermediates → final), sharing a playhead.

No animated transitions anywhere, by design.

## Layout

```
index.html            the whole deck — 26 slides, content and styling inline
media/audio/          36 excerpts cut from session recordings and renders
media/video/          latent collage SC interface demo
media/img/            session photos, FlowEdit paper figure
TODO-MEDIA.md         outstanding photos, screenshots and video to shoot
```

Audio excerpts were cut with ffmpeg from the originals under
`~/Documents/2026/MIT/recordings/coleman/`,
`sa-flowedit/flowedit_out/` and `concatenator-corpus/`. Sources untouched; see
`TODO-MEDIA.md` to re-cut or swap any clip.

## ⚠️ Private, and why

- **Performers' voices.** Every voice clip is Anna, Grisha, Raymond, Sora, Josh
  or Jon, from the 17/23/30 July sessions. Nobody has been asked about
  distribution. Making this repo public requires asking them first.
- **A commercial track.** `media/audio/target_pp.mp3` is 30 s of Bill Converse,
  "Phantom Pain", used as a musaicing target for internal reference.
- **A paper figure.** `media/img/flowedit_fig1.png` is Figure 1 of
  Kulikov et al., arXiv:2412.08629, reproduced for a talk.
- **The Concatenator** (Tralie & Cantil, ISMIR 2024, arXiv:2411.04366) is
  **CC BY-NC-ND** — attribution is required wherever any of this is shown, and
  modified versions of the tool must not be redistributed.

## Credits

Choreography Grisha Coleman, with Anna Huang; coordination Amira Samiy;
production MIT Future Fest. The FlowEdit server this work forks from was built by
Nithya Shikarpur. Aeolian harp and ebow recordings courtesy of Michael Krzyzaniak.
Deck by Jon Myers, Human–AI Resonance Group.
