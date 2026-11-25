# Ultimate Pickleball Clash

A 3D, 2v2 pickleball game that runs in a desktop or phone browser. Built with Three.js; each page is a single HTML file with no build step.

| File | What it is |
| --- | --- |
| `index.html` | The game: pick one of 12 players, Classic or Ultimate mode, Easy/Normal/Hard rivals |
| `characters.html` | Character page: the 12 preset players on turntables, each with their ultimate |
| `ultimates.html` | Ultimate Lab: practice court for testing the 12 ultimates |
| `courts.html` | Court viewer: look around the Park, Gym and Backyard courts, with a draw-call readout |

Open `index.html` in a browser to play (an internet connection is needed to load Three.js).

## How a match starts

1. **Choose your player:** 15 seconds to pick one of the 12. A "Hurry!" warning shows for the last 5 seconds, and at 0 you get a random player.
2. **Match intro:** all four players appear (name, role and ultimate), then a coin toss decides which team serves first. The screen lasts up to 15 seconds; press Enter or Esc, or tap Skip, to start at once.

The main menu shows your most recent game; the two before it fold under "older games".

## Courts

The court is set by the Rivals difficulty. Only the surroundings change; the court and the rules are the same everywhere.

| Rivals | Court | Surroundings |
| --- | --- | --- |
| Easy | Backyard | A concrete pad on the lawn, a wooden fence, the house and patio, seven friends standing around |
| Normal | Gym | An indoor rec center (SD Rec Center) with a wood floor, half-full bleachers and basketball hoops |
| Hard | Park | The original outdoor court: chain-link fence, full bleachers, light poles and pine trees |

All courts are flat-coloured low poly, with repeated props drawn in batches, so they run on phones.

## Keeping copies in sync

Some code is copied between pages so each page stays a single file:

- The character factory and the 12-player roster: `index.html` and `characters.html`.
- The court and venue code (COURT through VENUES): `index.html` and `courts.html`.
- The ultimate settings (for example `QUAKE`, `HOLE`): `index.html` and `ultimates.html`.

When you change one copy, change the other too. Comments in the code mark the copied character and court sections.

## Disclosure

- **Title:** Ultimate Pickleball Clash
- **Genre:** Sports
- **Developer:** Ken (from San Diego)
- **Release Year:** 2026

Free to play and share for non-commercial use; not for resale.

This project is a fan fiction and is in no way affiliated with, endorsed by, or associated with anyone named in the game.

All AI-generated content was reviewed, refined, and integrated by the developer to ensure consistency with the game's artistic direction and quality standards.

The primary goal of this Pickleball game project is for pickleball educational and research purpose only.
