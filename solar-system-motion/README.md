# Solar System in Motion

An animated, self-contained illustration of how the Solar System moves
through space, in four nested scales:

1. **Around the Sun** – the familiar heliocentric view with real orbital periods.
2. **Through the galaxy** – following the Sun at 230 km/s, the planets trace
   helices around its path. A switch shows the true proportions (48 AU of
   forward travel per Earth orbit) instead of the compressed view.
3. **Around the galaxy** – the Sun's 230-million-year orbit around the Milky
   Way, with an edge-on inset of its vertical bobbing through the disc.
4. **Toward Andromeda** – the Milky Way and M31 falling toward each other,
   meeting in about 4.5 billion years, while the Local Group drifts against
   the cosmic microwave background.

A speed ladder beside the narration lists every motion Earth is taking part
in at once, from rotation (0.46 km/s) to the Local Group's drift (~620 km/s).

Open `index.html` in any browser. No build step and no dependencies (the
only external resource is a Google Fonts stylesheet, with system fallbacks
if it is unavailable).

Controls: Play / Pause, Restart, speed (½×, 1×, 2×, 4×), scale chips to
jump between scenes, and a "True proportions" switch on scale 2. Space
plays or pauses, Left and Right change scale, R restarts. Respects
`prefers-reduced-motion` (starts paused).

Simplifications are noted on the page: orbit spacing is compressed at
scale 1, planets and galaxies are enlarged, and the galactic disc rotates
rigidly at scale 3.
