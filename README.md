# corpora-cafe 🥤

A pixel drink counter where every tap pours a real linguistics corpus, word by word, with physics.

**[▶ Play it here](https://brezgis.github.io/corpora-cafe/)**

![The soda fountain pouring COCA into a big cup, an ice cascade, and a rainbow of kaomoji filling a glass](screenshots/shot-fountain.png)

## What is this

A hard-pixel, early-2000s-web-style café built as one self-contained HTML file.
The soda fountain dispenses corpora. The espresso machine pulls timed shots of
Dante. The tea urns hold the Universal Declaration of Human Rights in three
languages, steeping as visible tokens. Everything you pour falls as words,
collapses into characters when it lands in a glass, and stacks into a drink
you can garnish, steam, slurp — or spill, and then mop up with the rag from
the SANI bucket. There are no instructions; poke at things.

## Quickstart

Open `index.html` in a browser. There is no build step, there are no
dependencies, and nothing is requested from any other server. You can also
serve the folder with any static server.

`♪ jazz` in the corner puts on a shuffled stack of real recordings from the
`music/` folder, and `»` skips to the next one. The name of the track that is
playing appears beside the chips and links to its source. Nothing in `music/`
is downloaded until you press the chip. If the recordings cannot load, a little
brushed piano trio plays instead, generated live in your browser with Web
Audio. `ⓘ` has the credits.

## On tap

| Tap | Corpus |
|---|---|
| BROWN | [The Brown Corpus](https://en.wikipedia.org/wiki/Brown_Corpus) (1961), the original million-word corpus of American English: ~100 real sentences sampled across all 15 genres, opening with the Fulton County Grand Jury |
| COCA | in the spirit of the [Corpus of Contemporary American English](https://www.english-corpora.org/coca/): original lines written in its eight genres (COCA itself can't be redistributed) |
| SWITCHBOARD | [telephone speech](https://catalog.ldc.upenn.edu/LDC97S62), uh, you know [laughter]: original A:/B: exchanges in its transcription style, on its real call topics (also licensed, so not quoted) |
| WORDNET | [Princeton WordNet](https://wordnet.princeton.edu/) 3.0 synsets and glosses, with a few hypernym chains |
| πUP | [the digits of π](https://en.wikipedia.org/wiki/Pi), computed live (Machin's formula) so it really never repeats |
| MAGIC MOJI | [kaomoji](https://en.wikipedia.org/wiki/Kaomoji), rainbow-fresh (ノ◕ヮ◕)ノ*:・゚✧ — about seventy of them |
| espresso | Dante, [Divina Commedia](https://en.wikipedia.org/wiki/Divine_Comedy): all of *Inferno* I, shot after shot, then a few famous tercets through the last line of *Paradiso* |
| teas | the [UDHR](https://www.un.org/en/about-us/universal-declaration-of-human-rights) in French, Japanese, and Spanish: the same 18 articles in each, aligned like the parallel corpus it is (Japanese is word-segmented as it pours) |
| milks | [lorem ipsum](https://en.wikipedia.org/wiki/Lorem_ipsum) (MILK), the Cicero it was scrambled from, *De finibus* 1.10.32–33 (OAT, SOY), and H. Rackham's 1914 translation (UBE) |
| whip | three words of [Devo](https://en.wikipedia.org/wiki/Whip_It_(Devo_song)), floats as a cap |
| KOFEMOLKA | grinds words into punctuation |

Every dispenser keeps pouring from where it left off: sampled corpora
shuffle their sentences (none repeats until the whole bag has poured),
continuous texts run in order.

## More of the room

![The SMOL two-group espresso machine with demitasses and a spilled shot](screenshots/shot-espresso.png)

![Transparent tea urns full of steeping UDHR tokens, pouring through the riser](screenshots/shot-urns.png)

![The whole counter](screenshots/shot-full.png)

Everything is drawn at your screen's real pixel density, with the pixel art
snapped to whole device pixels, and the physics runs at a fixed 60 steps a
second whatever your display's refresh rate.

The backsplash is a real museum piece: [*Tile with 'Saz' Leaf Design*](https://www.metmuseum.org/art/collection/search/452854),
Iznik, ca. 1545–55, from The Met's open-access collection (public domain).

## Music

The café plays nine recordings that are either in the public domain or
released under licenses that allow them to be hosted here. Every file in
`music/` was re-encoded to MP3 and levelled to a common volume. "Stardust"
was also trimmed at both ends to remove the applause, and "On the Alamo" was
band-limited to soften the surface noise of the 78. Nothing else was changed.

| Track | Artist | Source | License |
|---|---|---|---|
| Jazz Brunch | Kevin MacLeod | [incompetech.com](https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1700074) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Bossa Antigua | Kevin MacLeod | [incompetech.com](https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1700069) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Backbay Lounge | Kevin MacLeod | [incompetech.com](https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1700068) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Lobby Time | Kevin MacLeod | [incompetech.com](https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1600054) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| 2 (jazz), from *Busted Guitar (JAZZ)* | HoliznaCC0 | [Free Music Archive](https://freemusicarchive.org/music/holiznacc0/busted-guitar-jazz/2-jazz/) | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |
| 4 (jazz), from *Busted Guitar (JAZZ)* | HoliznaCC0 | [Free Music Archive](https://freemusicarchive.org/music/holiznacc0/busted-guitar-jazz/4-jazz/) | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |
| You da Bossa, from *Jazz Hop* | Ketsa | [Free Music Archive](https://freemusicarchive.org/music/Ketsa/jazz-hop-1/you-da-bossa/) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Stardust, from *Live at Blues Alley* | U.S. Army Blues | [Free Music Archive](https://freemusicarchive.org/music/US_Army_Blues/Live_At_Blues_Alley/0_-_05_-_The_US_Army_Blues_-_Stardust/) | Public domain ([Public Domain Mark 1.0](https://creativecommons.org/publicdomain/mark/1.0/)). The recording is a work of the United States Army, and Hoagy Carmichael's 1927 composition is out of copyright in the United States. |
| On the Alamo (Victor 18931, recorded 17 July 1922) | Benson Orchestra of Chicago | [Library of Congress National Jukebox, by way of the Internet Archive](https://archive.org/details/loc-jukebox-63520-on-the-alamo) | Public domain in the United States. Sound recordings published before 1926 have left copyright under the Music Modernization Act, and Isham Jones's 1922 composition has as well. |

The MIT license below covers the code and does not cover the files in `music/`,
which keep the terms listed in this table.

## License

[MIT](LICENSE)

---

a [sharabara](https://brezgis.github.io) production ♡
