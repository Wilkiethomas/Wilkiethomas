# Solar System in Motion

A real-time 3D (WebGL) animation of how the Solar System moves through
space, in four nested scales. Drag to orbit the camera, scroll or pinch to
zoom.

1. **Around the Sun** – the familiar heliocentric view with real orbital periods.
2. **Through the galaxy** – following the Sun at 230 km/s, the planets trace
   helices around its path. A switch shows the true proportions (48 AU of
   forward travel per Earth orbit) instead of the compressed view.
3. **Around the galaxy** – the Sun's 230-million-year orbit around a
   volumetric Milky Way (bulge, thin disc, four arms, dust lanes), with
   oblique, overhead and edge-on views; the edge-on view shows the Sun's
   vertical bobbing through the disc as a wave in its trail.
4. **Toward Andromeda** – the Milky Way and M31 falling toward each other,
   meeting in about 4.5 billion years, while the Local Group drifts against
   the cosmic microwave background.

A speed ladder beside the narration lists every motion Earth is taking part
in at once, from rotation (0.46 km/s) to the Local Group's drift (~620 km/s).

Open `index.html` in any browser with WebGL. No build step. It loads
Three.js r128 and its OrbitControls from cdnjs, plus a Google Fonts
stylesheet (with system fallbacks). Planet surfaces, the Sun's granulation,
atmospheres, Saturn's rings, the star field and the galaxies are all
generated procedurally at load time; no image assets are used.

Controls: Play / Pause, Restart, speed (½×, 1×, 2×, 4×), scale chips to
jump between scenes, a "True proportions" switch on scale 2 and a View
switch on scale 3. Space plays or pauses, Left and Right change scale,
R restarts, V cycles the view. Respects `prefers-reduced-motion` (starts
paused, no auto-rotation).

Simplifications are noted on the page: orbit spacing is compressed at
scale 1, planets and galaxies are enlarged, planet spin is slowed, the
Sun's vertical bobbing is exaggerated tenfold at scale 3, and the galactic
disc there rotates rigidly.
