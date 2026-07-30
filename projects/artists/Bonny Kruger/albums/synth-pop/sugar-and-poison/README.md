---
title: "Sugar and Poison"
release_date: ""  # YYYY-MM-DD (fill in when releasing)
genres: ["synth-pop", "pop"]
tags: ["concept-album", "double-album", "bilingual", "psychological", "literary-inspired"]
explicit: true  # tentative — several tracks flagged Yes pending explicit-checker at lyric-writing
# anchor_track: null  # Optional: 1-based track number to anchor album mastering (issue #290). Empty = auto-select by composite score.
streaming:
  soundcloud: ""    # Fill in when released
  spotify: ""       # Fill in when released
  apple_music: ""   # Fill in when released
  youtube_music: "" # Fill in when released
  amazon_music: ""  # Fill in when released
sheet_music:
  songbook: ""
# mastering:  # Optional - per-album mastering settings
#   adm_validation_enabled: true
# slug: ""  # Optional - only uncomment if you need to override auto-generated slug
---

# Sugar and Poison

## Album Details

<!-- NOTE: When releasing, set Status: Released and fill in release_date in frontmatter. Albums stay in place. -->

| Attribute | Detail |
|-----------|--------|
| **Artist** | [Bonny Kruger](../../../README.md) |
| **Album** | Sugar and Poison |
| **Genre** | [Synth-Pop](/genres/synth-pop/README.md) / Pop |
| **Tracks** | 16 (15 vocal, 1 instrumental) + 1 bonus track |
| **Status** | Concept |
| **Explicit** | Yes (tentative — several tracks pending explicit-checker) |
| **Concept** | Debut double album reframing Alice in Wonderland as a psychological unraveling of identity. English is the controlled, performed "mask" register; Swedish is the raw inner voice that breaks through when the mask cracks. Candy-coated synth-pop surface, dark psychological undertow. |

## Frontmatter Reference

### mastering (optional)

Per-album mastering settings. Currently supports:

- `adm_validation_enabled: true` — opt in to Apple Digital Masters
  inter-sample peak validation. **Defaults to OFF** even when
  global `config.yaml::mastering.adm_validation_enabled` is `true`.
  ADM runs the AAC encode/decode check on every mastered file and
  can add 3-5 min/track to the pipeline. Only enable when the
  album's source material is spectrally viable (well-balanced
  highs) AND you're submitting the album for Apple Digital Masters
  certification. For most Suno-generated albums, leave this off.

Example (opt in for this album only):

```yaml
mastering:
  adm_validation_enabled: true
```

Omit the block entirely to use the default (ADM off).

## Concept

*Sugar and Poison* is Bonny Kruger's debut album, a thematic concept album that uses Lewis Carroll's *Alice's Adventures in Wonderland* and *Through the Looking-Glass* (public domain, 1865/1871) as a lens for identity fragmentation and reintegration, not a literal retelling. Alice is not a fictional character being described from outside — Bonny sings *as* Alice throughout, in first person.

The album's central device is linguistic: **English is the mask** — the controlled, polished, performing self, singing in pop's default language. **Swedish is the raw inner voice** — unfiltered, direct, breaking through whenever the mask cracks. The Cheshire Cat is personified as this raw voice's recurring embodiment: a filtered, pitched vocal motif that reappears across multiple tracks, not just its own song.

Wonderland set-pieces (the bottle, the tea party, the Queen's court, the trial, the Jabberwocky, the looking-glass) are used as psychological anchors — loss of bodily control, forced social performance, internalized perfectionism, judgment without evidence, confronting one's worst self, and finally, an ambiguous, only partly resolved integration of the two voices. It is not a redemption arc; it's a truce.

*Note on source: inspired by Carroll's original text (public domain). Deliberately avoids specific imagery/character designs from copyrighted adaptations (e.g. Disney's 1951 film).*

## Structure

Five loose acts, tracked across 16 songs:

- **Act I — The Fall** (01–04): curiosity slides into loss of control. Mask (English) fully intact.
- **Act II — Unreliable Guides** (05–08): confusion despite company; the mask visibly cracks for the first time at the centerpiece (track 8).
- **Act III — Breakdown** (09–12): total collapse — self-judgment, chaos, trial, overwhelm. The album's most sustained high-energy stretch, deliberately relentless.
- **Act IV — Confrontation** (13–14): turning to face the internal monster and then the mirror, for the first time on her own terms.
- **Act V — Integration** (15–16): no rescue, but a fragile truce between mask and raw voice — ambiguous, not saccharine.

## Themes

- Identity fragmentation and reintegration under psychological pressure
- The performed self vs. the raw, unfiltered self (mask vs. voice)
- Internalized authority and self-judgment mistaken for external threat
- Loss of bodily/self-image control
- Coping through absurd logic and chosen, imperfect belief (not a cure)

## Motifs & Threads

### Lyrical Motifs

| Motif | Description | First Appears | Recurrences |
|-------|-------------|---------------|-------------|
| "Curiouser and curiouser" | Nyfiket förundran, glider till bitter ironi | Track 01, 04 | Track 11 (ironic, under judgment) |
| "Off with her head" | Yttre dom → internaliserad självdom | Track 09 | Track 11 (whispered), Track 16 (returns, ignored) |
| Pocket-watch ticking (SFX) | Tidsångest, accelererar mot kollaps | Track 02 | Track 04 (faster), Track 11 (fastest), Track 16 (stops/breaks) |
| English mask / Swedish raw voice | The core device — controlled performance vs. unfiltered truth | Track 01 (mask only) | Every track; first crack Track 03, thesis stated Track 08, first blend Track 15, integrated Track 16 |
| "Vem är jag" (who am I) | Raw, unfiltered central question, first spoken in panic | Track 03 (bridge) | Strong candidate for recurrence at Track 08, 14, 16 — not yet confirmed, flag when those tracks are written |
| "That careful hand" | The bottle's handwriting, then doubted as possibly her own | Track 03 (Verse 1 → Pre-Bridge) | Intra-song callback only so far; available for later tracks (e.g. Track 14's mirror/self-recognition) |

### Character Threads

| Character/Voice | Arc Summary | Tracks |
|-----------------|-------------|--------|
| Cheshire Cat (filtered/pitched SE vocal motif) | Introduced as a teasing, unreliable guide; recurs as a background whisper/laugh in increasingly tense contexts; present for the last time at the confrontation, then absent from the resolution | 05, 06, 09, 10, 13 |
| The Queen of Hearts / "the verdict" | Internalized authority — external judgment revealed to be self-judgment | 09, 11, 16 |
| Alice's reflection | The self Alice can't yet face directly; finally addressed, not fought, in the climax | 08 (indirect, via Tweedle duality), 14 (direct) |

### Thematic Progression

| Track | Theme Focus | Advances From | Sets Up |
|-------|-------------|---------------|---------|
| 01 | Performed contentment, first crack | — | The mask/raw-voice device before it's named |
| 02 | Loss of ground, fall | Track 01's unease | Ticking-watch motif |
| 03 | Loss of bodily control | Track 02's disorientation | The mask/raw language mechanic, demonstrated for the first time |
| 04 | Forced composure under acceleration | Track 03's crack | "Curiouser" motif that pays off bitterly in Track 11 |
| 05 | Unreliable guidance | Track 04's fraying calm | Cheshire Cat as recurring inner-voice motif |
| 06 | Forced social performance | Track 05's teasing tone turns performative | Mask register at its most extreme, right before it visibly cracks |
| 07 | Pure disorientation (instrumental) | Track 06's excess | A wordless breath before the album's thesis statement |
| 08 | Mask vs. raw voice addressed directly (title track) | Track 07's disorientation | The album's central duality named outright — everything after either fights or resolves it |
| 09 | Internalized self-judgment | Track 08's confrontation | "Off with her head" motif |
| 10 | Rules changing without warning | Track 09's judgment | Momentum into the trial |
| 11 | Judged without evidence — structural peak | Tracks 04, 09's motifs converge | Full collapse into Track 12 |
| 12 | Total overwhelm | Track 11's collapse | The emptiness that Act IV must respond to |
| 13 | Facing the internal monster | Track 12's emptiness | First time mask and raw voice fight on the same side |
| 14 | Self-recognition without judgment | Track 13's confrontation | First real dialogue between the two registers |
| 15 | Chosen, imperfect belief | Track 14's dialogue | First blended (not alternating) use of both languages |
| 16 | Ambiguous integration | Track 15's blend | Callback to Track 01's setting; ticking motif resolves |

*Seeded by album-conceptualizer during Phase 4. Updated by lyric-writer as tracks are written.*

## Sonic Palette

- **Beats**: Candy-coated darkness — bright, quantized synth-pop surfaces with sudden warped/distorted/detuned breaks when the mask cracks. Production register itself doubles as the mask/raw-voice device: synthetic and clean for mask sections, live-feeling (real-sounding strings, unpolished piano) bleeding in for raw sections.
- **Samples**: Detuned music-box/carousel motif, ticking pocket-watch SFX, filtered/pitched Cheshire Cat vocal ad-libs
- **Vocals**: First-person throughout (Bonny as Alice). Two registers: processed/clean English "mask" vocal vs. raw/unprocessed Swedish "voice" vocal — the split is the album's structural spine, not a stylistic flourish
- **Mood**: Bright and unsettling at once — a children's picture book rotting at the edges. Reference direction: candy-coated dark synth-pop in the vein of Melanie Martinez, but pushed toward its own identity via the bilingual mask/voice device and the specific Wonderland-as-psychology framing

## Tracklist

| # | Title | POV | Concept | Status |
|---|-------|-----|---------|--------|
| 01 | [Golden Afternoon](tracks/01-golden-afternoon.md) | Mask (EN) | Idyllic opener, first crack | Not Started |
| 02 | [Rabbit Hole](tracks/02-rabbit-hole.md) | Mask (EN) | The fall | Not Started |
| 03 | [Drink Me](tracks/03-drink-me.md) | Mask (EN) / Raw (SE) | Body loses control — device introduced | In Progress |
| 04 | [Curiouser](tracks/04-curiouser.md) | Mask (EN) | Forced composure accelerating | Not Started |
| 05 | [Cheshire](tracks/05-cheshire.md) | Mask (EN) + Cat (SE) | Unreliable guidance | Not Started |
| 06 | [Unbirthday](tracks/06-unbirthday.md) | Mask (EN) | Forced celebration, peak mask | Not Started |
| 07 | [Tulgey Wood](tracks/07-tulgey-wood.md) | — (instrumental) | Pure disorientation | Not Started |
| 08 | [Sugar and Poison](tracks/08-sugar-and-poison.md) | Mask + Raw | Title track — the thesis stated | Not Started |
| 09 | [Off With Her Head](tracks/09-off-with-her-head.md) | Mask (EN) / Raw (SE) | Internalized self-judgment | Not Started |
| 10 | [Croquet](tracks/10-croquet.md) | Mask (EN) | Rules changing, short burst | Not Started |
| 11 | [The Trial](tracks/11-the-trial.md) | Mask collapsing into Raw | Structural peak — judged without evidence | Not Started |
| 12 | [Pool of Tears](tracks/12-pool-of-tears.md) | Raw (SE) | Total overwhelm | Not Started |
| 13 | [Jabberwocky](tracks/13-jabberwocky.md) | Mask + Raw (layered) | Confronting the inner monster | Not Started |
| 14 | [Looking Glass](tracks/14-looking-glass.md) | Mask/Raw duet | Self-recognition | Not Started |
| 15 | [Six Impossible Things](tracks/15-six-impossible-things.md) | Mask + Raw (blended) | Chosen, fragile belief | Not Started |
| 16 | [Waking](tracks/16-waking.md) | Mask + Raw (integrated) | Ambiguous resolution | Not Started |

**Bonus track (outside the five-act arc):**

| # | Title | POV | Concept | Status |
|---|-------|-----|---------|--------|
| 17 | [Övertänker](tracks/17-övertänker.md) | Jag (first person), addressing intrusive thoughts as "du" | All-Swedish standalone track — overthinking/anxiety spiral, cyberpunk industrial verses into K-pop pop-bounce chorus. No Alice framing, no mask/voice device — shares the album's candy-coated-darkness instinct via a different mechanism. | In Progress |

**Track 17 Style Box** (differs from the album base — bonus track, own sound):
```
Female vocal, cold detached delivery in verses shifting to bright belting in
chorus. Genre-fluid: cyberpunk industrial verses into K-pop pop-bounce chorus
with EDM synth drop. 124 BPM, A minor. Verses: pulsing analog bass, glitchy
digital artifacts, sparse cold synth pads, claustrophobic, minimal drums.
Chorus: glossy maximalist production, EDM bounce drop, layered vocal
harmonies, chant ad-libs, bright synth stabs, four-on-the-floor kick.
Bridge: industrial breakdown, distorted low synth, rising tension.
```

## Production Notes

<!-- SERVICE: suno -->
**Suno Persona** (optional):
| Attribute | Value |
|-----------|-------|
| **Persona Name** | — (not yet created) |
| **Persona Link** | — |

**Suno Settings**:
- **Target Duration**: 3:30–4:30 standard, with Tulgey Wood (~1:30–2:00, instrumental) and Croquet (~2:00–2:30) as intentional exceptions
- Per-track overrides noted in individual track files
- Maintain a consistent lead vocal identity across the album for the "mask" (English) register; the "raw" (Swedish) register should sound distinctly less processed/more intimate even when it's the same performer
- Cheshire Cat motif (filtered/pitched Swedish vocal ad-lib) should use a consistent processing chain across every track it appears in (05, 06, 09, 10, 13) so it reads as one recurring "character"

**Style Prompt Base**:
```
synth-pop, pop, candy-coated dark pop, bright synth arps and warm pads with sudden detuned/distorted breaks, female pop vocal, bilingual (English/Swedish), modern polished production with organic elements (strings, piano) bleeding in during raw/vulnerable sections
```
<!-- /SERVICE: suno -->

## Distributor Genres

| Attribute | Selection |
|-----------|-----------|
| **Primary Genre** | Pop |
| **Secondary Genre** | Alternative |
| **Electronic Subgenre** | N/A |

## Album Art

### AI Art Platform
<!-- Set your platform: Midjourney, Leonardo.ai, DALL-E, Stable Diffusion -->
**Platform**: [Not selected]

**Direction notes (from concept phase, to hand off to album-art-director)**: Pastel palette (bubblegum pink, mint, baby blue) corrupted by rust/blood-red cracks and ink-black shadows — a children's picture book rotting at the edges. Should read as inviting at a glance, wrong on a second look.

### Image Prompt
*Generated by `/bitwize-music:album-art-director`. Platform-specific format.*

```
[Prompt will be generated in the format matching your selected platform.
Run /bitwize-music:album-art-director to create a visual concept and prompt.]
```

### Negative Prompt
<!-- Leonardo.ai / Stable Diffusion only. Remove this section if using Midjourney or DALL-E. -->
```
[Elements to exclude — only applicable for Leonardo.ai and Stable Diffusion]
```

**Note**: Artist name should always appear in the bottom right. Preserve the artist's preferred casing/spelling.

### File Naming Convention

Save generated album art using `/bitwize-music:import-art` or manually to these locations:
- **Audio directory**: `{audio_root}/artists/{artist}/albums/{genre}/{album}/album.png` (used by promo videos, SoundCloud)
- **Content directory**: `{content_root}/artists/{artist}/albums/{genre}/{album}/album-art.png` (tracked in git)

Format: PNG preferred, JPEG acceptable. Resolution: at least 3000x3000 for distribution, 1500x1500 minimum.

## SoundCloud

### Description
*Copy this into SoundCloud's description field:*

```
Sugar and Poison — the debut album from Bonny Kruger.

A synth-pop concept album that reframes Alice in Wonderland as a psychological unraveling: English is the mask, Swedish is the voice underneath it. Candy-coated on the surface, something darker running through it.
```

### Genre
```
Pop
```

### Tags
```
synth-pop, dark pop, concept album, Alice in Wonderland, bilingual
```

---

## Release Info

*(Fill in this section when album is complete and released)*

| Attribute | Detail |
|-----------|--------|
| **Released** | [Month Year] |

### Track Listing

| # | Title | Duration | Listen |
|---|-------|----------|--------|
| 01 | [Track Name] | 0:00 | [SoundCloud](URL) |
