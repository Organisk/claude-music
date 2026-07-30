---
title: "Slumberland"
release_date: ""  # YYYY-MM-DD (fill in when releasing)
genres: ["pop", "synth-pop"]
tags: ["concept-album", "psychological", "alice-in-wonderland-inspired", "debut"]
explicit: false  # true or false
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

# Slumberland

## Album Details

<!-- NOTE: When releasing, set Status: Released and fill in release_date in frontmatter. Albums stay in place. -->

| Attribute | Detail |
|-----------|--------|
| **Artist** | [Bonny Kruger](../../../README.md) |
| **Album** | Slumberland |
| **Genre** | Pop / Synth-pop |
| **Tracks** | 16 |
| **Status** | In Progress |
| **Explicit** | No |
| **Concept** | An amnesiac Alice wakes in Slumberland — a dream-state Wonderland — and plays a literal game of hide-and-seek with the fragments of her own forgotten identity. Debut double album for Bonny Kruger. |

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

Alice wakes up — or falls asleep into — **Slumberland**, a dream-version of Wonderland, with no memory of who she is or how she got there. The Wonderland figures aren't characters she meets; they're **externalized fragments of her own fractured psyche**. The album is, literally, a game of hide-and-seek between Alice and her own forgotten self: some tracks retreat and hide from the truth (denial, dissociation, comfort in forgetting), others chase and confront it (urgency, self-punishment, the terror of remembering).

This is a **thematic** album, not a straight narrative retelling — Wonderland's imagery (the rabbit hole, the tea party, the Cheshire grin, the Queen's garden) is used to explore memory, dissociation, and self-erasure, sung entirely in first person as Alice. It draws on the public-domain Lewis Carroll source material only; no copyrighted adaptation elements (Disney designs, etc.) are used.

## Structure

The album alternates **Hide** and **Seek** tracks as its core pacing mechanic — Hide tracks are lower-energy, retreating, dissociative; Seek tracks are higher-energy, urgent, confrontational. This alternation drives the energy map and keeps no more than two tracks at the same intensity in a row.

**Energy map** (16 tracks, two 8-track sides — *Falling* / *Seeking*):

```
01 (Intro):  ▂▂▂ Low, atmospheric — the game begins
02:          ▆▆▆ Building — White Rabbit urgency
03:          ████ Peak — title track, first single
04:          ▄▄▄ Mid — Cheshire Cat duality
05:          ▂▂▂ Valley — first memory fragment
06:          ▅▅▅ Building — Mad Hatter loop
07:          ▆▆▆ Centerpiece — "Paint It Red"
08:          ████ Peak — Queen of Hearts
09:          ▄▄▄ Mid — Caterpillar confrontation
10:          ▂▂▂ Valley — dissociation
11:          ▅▅▅ Building — hope, a name returns
12:          ████ Peak — the figures resist
13:          ▆▆▆ Building/tense — unraveling
14:          ▂▂▂ Valley — the truth beneath it all
15:          █████ Climax — nearly remembering
16 (Outro):  ▂▂▂ Resolution — wake, or stay asleep?
```

Emotional arc: disorientation → playing along with the game → glimpses of memory → the psyche-figures resisting her return → a near-remembering climax → an ambiguous, bittersweet ending.

## Themes

- Memory and amnesia as both flight and prison
- Identity as something hidden that must be found again
- Self-punishment and the fear of consequence (Queen of Hearts / "painting the roses red")
- Dissociation — seeing oneself as a stranger
- The seductive comfort of forgetting versus the terror of it

## Motifs & Threads

### Lyrical Motifs

| Motif | Description | First Appears | Recurrences |
|-------|-------------|---------------|-------------|
| Painted roses (white → blood-red) | Covering the truth/innocence with guilt and forced compliance to survive the Queen's judgment | Track 07 | Track 08 (the fear that demands the cover-up), Track 14 (the white truth glimpsed again beneath the paint), Track 16 (ambiguous — paint fading or freshly reapplied) |
| "Count to ten" / the game | The ritual of hiding from oneself; rules the psyche imposes on its own search | Track 01 | Track 02 (distorts into anxious clock-ticking, "tick by tick by tick"), Track 03 (title track hook "ready or not", whispered outro reprises the countdown), Track 16 (reprise — the count resumes or finally ends) |
| The mirror / reflection | Dissociation; seeing the self as a stranger | Track 10 | Track 15 (the mirror shatters or clarifies at the climax) |
| Slumberland (the place itself) | The dream-state as both sanctuary and prison | Track 01 | Track 16 (reprise, title callback) |
| The Room (three memory-fragments) | A room holding disordered fragments of memory — practical/reasoned knowledge, love-and-pain, and what's slipped past recall entirely; the first crack in the amnesia | Track 05 | — |

### Character Threads

| Character/Voice | Arc Summary | Tracks |
|-----------------|-------------|--------|
| White Rabbit | Anxiety and time-pressure that escalates until the final confrontation | 02, 06, 15 |
| Cheshire Cat | Mocking, dualistic inner voice undermining every attempt to remember | 04, 09, 12 |
| Mad Hatter | Obsessive repetition and temporal disorientation | 06, 13 |
| Queen of Hearts | Self-punishing inner critic; the fear that drives the hiding | 07, 08, 12 |
| Caterpillar | The existential question at the album's center — "who are you?" | 09, 14 |
| Mirror/Looking Glass | Dissociation; culminates in shattering (confrontation) or clarity (acceptance) | 10, 15, 16 |

### Thematic Progression

| Track | Theme Focus | Advances From | Sets Up |
|-------|-------------|---------------|---------|
| 01 | Dreamlike entry into Slumberland; the game begins | — | The "count to ten" framing and the reprise melody |
| 02 | Anxiety and urgency of forgetting | Track 01's dream-logic entry | The ticking-clock tension recurring through Seek tracks |
| 03 | The game as coping mechanism — hiding is safer than finding | Track 02's urgency | The title hook, recalled in the outro |
| 04 | The mocking inner voice, duality | Track 03's hiding impulse | Cheshire Cat voice returning in Tracks 9 and 12 |
| 05 | First real memory fragment surfaces | Track 04's unease | The "room" image as a symbol of buried memory |
| 06 | Obsessive repetition, time distortion | Track 05's fragment | The confrontation with repeating trauma in Track 7 |
| 07 | Confronting the central motif — painting over the truth | Track 06's loop | The blood-red/white motif recurring through the rest of the album |
| 08 | Self-punishment, fear of consequence | Track 07's confrontation | The judgment/fear driving the hiding in Tracks 9–10 |
| 09 | Existential confrontation — "who are you" | Track 08's fear | Forces the identity question the second half must answer |
| 10 | Full dissociation, seeing self as a stranger | Track 09's question | The mirror image returning in Track 15's climax |
| 11 | First real hope — a name almost remembered | Track 10's dissociation | The resistance staged in Track 12 |
| 12 | The psyche fights the return of memory | Track 11's hope | Escalates directly into Track 13's unraveling |
| 13 | Everything comes loose | Track 12's resistance | The quiet truth of Track 14 |
| 14 | The truth beneath it all — who she was before | Track 13's unraveling | The full confrontation of Track 15 |
| 15 | Climax — nearly remembering everything at once | Track 14's revelation | Leaves the ending open for Track 16 |
| 16 | Resolution — the choice between waking and staying asleep | Track 15's climax | Closes the loop back to Track 01's melody/framing |

*Seeded by album-conceptualizer during Phase 4. Updated by lyric-writer as tracks are written.*

## Sonic Palette

- **Beats**: Bright, glittering synth-pop production (Melanie Martinez-adjacent) with detuned/off-key elements bleeding through the polish — the "creepy lullaby" contrast between surface and undertow
- **Samples**: Music-box textures, distorted toy-piano/celesta, occasional tape-warble/vinyl-crackle suggesting a fading or aging memory
- **Vocals**: Clean lead vocal (Alice, first person) throughout; Wonderland archetypes voiced via pitched/distorted backing ad-libs and vocal chops, never as separate lead performances
- **Mood**: Whimsical surface, psychologically unsettling underneath — oscillates between comfort and dread

## Tracklist

| # | Title | POV | Concept | Status |
|---|-------|-----|---------|--------|
| 01 | [Slumberland (Intro)](tracks/01-slumberland-(intro).md) | Alice | Falling into the dream; the hide-and-seek game begins | In Progress |
| 02 | [Late (White Rabbit)](tracks/02-late-(white-rabbit).md) | Alice | Anxiety, urgency, the sense that time is running out | In Progress |
| 03 | [Hide and Seek](tracks/03-hide-and-seek.md) | Alice | Title track — the game as coping mechanism, playful-creepy hook | In Progress |
| 04 | [Grinning in the Dark](tracks/04-grinning-in-the-dark.md) | Alice | Cheshire Cat — the mocking, dualistic inner voice | Not Started |
| 05 | [A Room I Don't Remember](tracks/05-a-room-i-don't-remember.md) | Alice | First real memory fragment surfaces | In Progress |
| 06 | [Same Tea, Same Time](tracks/06-same-tea,-same-time.md) | Alice | Mad Hatter — obsessive repetition, time loop | Not Started |
| 07 | [Paint It Red](tracks/07-paint-it-red.md) | Alice | Centerpiece — the roses motif, painting over the truth | Not Started |
| 08 | [Off With Her Head](tracks/08-off-with-her-head.md) | Alice | Queen of Hearts — self-punishment, fear of consequence | Not Started |
| 09 | [Who Are You Supposed to Be](tracks/09-who-are-you-supposed-to-be.md) | Alice | Caterpillar — the existential confrontation | Not Started |
| 10 | [Stranger in the Mirror](tracks/10-stranger-in-the-mirror.md) | Alice | Full dissociation, seeing the self as a stranger | Not Started |
| 11 | [A Name I Almost Remember](tracks/11-a-name-i-almost-remember.md) | Alice | First real hope — a memory nearly breaks through | Not Started |
| 12 | [They Don't Want Me to Wake Up](tracks/12-they-don't-want-me-to-wake-up.md) | Alice | The Wonderland figures resist her return to herself | Not Started |
| 13 | [Unravel](tracks/13-unravel.md) | Alice | Everything starts coming loose | Not Started |
| 14 | [The Girl Before the Rabbit Hole](tracks/14-the-girl-before-the-rabbit-hole.md) | Alice | Quiet, devastating reveal — who she was before | Not Started |
| 15 | [Wide Awake (Almost)](tracks/15-wide-awake-(almost).md) | Alice | Climax — confronting all the figures/fragments at once | Not Started |
| 16 | [Stay Asleep With Me (Slumberland Reprise)](tracks/16-stay-asleep-with-me-(slumberland-reprise).md) | Alice | Ambiguous resolution — callback to the intro; does she wake? | Not Started |

## Key Characters

*(Psychological archetypes, not literal characters — see Character Threads above for arcs)*

### The Fragments
- **White Rabbit** - Anxiety and urgency; the ticking-clock pressure of forgetting
- **Cheshire Cat** - The mocking, dualistic inner voice that undermines every attempt to remember
- **Mad Hatter** - Obsessive repetition and temporal disorientation
- **Queen of Hearts** - The self-punishing inner critic; the fear that drives the hiding
- **Caterpillar** - The existential question at the album's core — "who are you?"
- **Mirror/Looking Glass** - Dissociation; the self seen as a stranger

## Production Notes

<!-- SERVICE: suno -->
**Suno Persona** (optional):
| Attribute | Value |
|-----------|-------|
| **Persona Name** | [Name in Suno] |
| **Persona Link** | [Suno persona URL] |

**Suno Settings**:
- **Target Duration**: 3:00–3:30 per track (keeps a 16-track double album tight rather than bloated)
- Per-track overrides noted in individual track files
- Single consistent lead vocal persona for Alice across all 16 tracks
- Wonderland archetype voices should use a consistent pitch/distortion processing chain across their recurring tracks (e.g., Cheshire Cat's pitched ad-lib treatment should sound the same in Tracks 4, 9, and 12)

**Style Prompt Base** (established via Tracks 01–03, proof of concept):
```
Clean female vocal, [track-specific delivery]. Synth-pop, dark pop [+ track-specific 3rd
genre term]. [2-3 track-specific instruments]. [Track-specific energy], glossy/candy-colored
production with an unsettling undertone bleeding through.

Baseline established: clean female lead throughout, "creepy lullaby" contrast (bright surface,
dark undertow) as the constant, Wonderland-archetype voices as pitched/distorted backing
ad-libs only (see Track 03's whispered "ready or not" ad-lib treatment as the reference point
for later archetype voices — Cheshire Cat, Mad Hatter, etc.).
```
<!-- /SERVICE: suno -->

## Album Art

### AI Art Platform
<!-- Set your platform: Midjourney, Leonardo.ai, DALL-E, Stable Diffusion -->
**Platform**: [Not selected]

### Image Prompt
*Generated by `/bitwize-music:album-art-director`. Platform-specific format.*

```
[Concept for album-art-director to develop: a girl in a nightgown (Alice) surrounded by
fragmenting, dreamlike Wonderland silhouettes; white and blood-red color palette throughout;
a recurring image of white roses being painted red; soft-focus edges and slightly-wrong
dream-logic perspective. Run /bitwize-music:album-art-director to generate the full prompt.]
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
Slumberland — an amnesiac Alice wakes in a dream-version of Wonderland with no memory of
who she is, and plays a game of hide-and-seek with the fragments of her own forgotten
identity. Debut album from Bonny Kruger.
```

### Genre
```
Pop
```

### Tags
```
synth-pop, concept album, dark pop, dream pop, alice in wonderland
```

## Distributor Genres

| Attribute | Selection |
|-----------|-----------|
| **Primary Genre** | Pop |
| **Secondary Genre** | None |
| **Electronic Subgenre** | N/A |

*Common primary genres: Hip-Hop/Rap, Electronic, Pop, Rock, R&B/Soul, Alternative, Metal, Folk, Country, Jazz, Classical, Soundtrack, Spoken Word*

*Electronic subgenres: Electronica/Downtempo, House, Deep House, Techno, Drum & Bass, Dubstep, Trance, Chill Out, Big Room, Breaks, Electro House, Glitch Hop, Minimal/Deep Tech, Progressive House, Psy-Trance, Tech House*

---

## Release Info

*(Fill in this section when album is complete and released)*

| Attribute | Detail |
|-----------|--------|
| **Released** | [Month Year] |

### Track Listing

| # | Title | Duration | Listen |
|---|-------|----------|--------|
| 01 | Slumberland (Intro) | 0:00 | [SoundCloud](URL) |
