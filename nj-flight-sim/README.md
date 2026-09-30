# Garden State Flight

A browser flight simulator for general aviation over New Jersey. Fly a
Cessna 172S Skyhawk or a Beechcraft Baron 58 from any of 31 real airports
in and around the state, over a map built from the real coastline, the
Delaware and Hudson rivers, Barnegat Bay, the Kittatinny and Watchung
ridges, the Pine Barrens, and the Manhattan and Philadelphia skylines.

Open `index.html` in a desktop browser (Chrome, Edge, Firefox or Safari).
It is a single file. The only external resources are three.js from a CDN
and a Google Fonts stylesheet.

## What is modelled

- Six-degree-of-freedom flight dynamics with lift, induced and parasite
  drag, flap and gear drag, stall with post-stall lift decay, ground
  effect, dihedral, weathervaning, adverse yaw, P-factor, and asymmetric
  thrust on the Baron when an engine is failed.
- Density altitude: engine power, thrust and indicated airspeed all follow
  the standard atmosphere.
- Spring-damper landing gear with brakes, nosewheel steering, tyre side
  force, hard-landing and belly-landing detection, wingtip and tail strikes.
- Realistic V-speeds, weights, wing area, inertia, power and prop limits
  for each aircraft, shown on the start screen.
- Airports with the real runway numbers and lengths, terrain flattened
  around the field, taxiway, apron, hangars, tower, windsock, rotating
  beacon and runway edge lights. The runway in use follows the wind.
- Six-pack instruments (airspeed with colour arcs, attitude, altimeter,
  turn coordinator with slip ball, directional gyro, vertical speed),
  tachometer and manifold pressure gauges, fuel, throttle quadrant, flap
  and trim indicators, and annunciators for stall, gear, fuel and engine
  failure. Headings are magnetic (12.5° W variation).
- Moving map with the state outline, highways and airports, at three zoom
  levels.
- Engine, wind, stall horn, gear horn and touchdown sounds.
- Keyboard, gamepad and touch controls; cockpit, chase, orbit and tower
  views; afternoon or dusk lighting; adjustable wind.

## Controls

| Action | Keys |
| --- | --- |
| Pitch (push / pull) | ↑ / ↓ |
| Roll | ← / → |
| Rudder and nosewheel steering | A / D |
| Throttle | W / S or PgUp / PgDn |
| Flaps down / up | F / V |
| Landing gear (Baron) | G |
| Wheel brakes (hold) | Space or B |
| Parking brake | P |
| Pitch trim | Home / End or [ / ] |
| Fail or restore engine 1 / 2 | 1 / 2 |
| Cycle view | C |
| Look around in the cockpit | mouse drag |
| Map zoom | M |
| Pause · Help · Reset | Esc · H · R |

## Flying tips

- Cessna: release the parking brake, full throttle, rotate at 55 knots,
  climb at 75. Approach at 65 with flaps 30, close the throttle over the
  numbers and hold the nose up.
- Baron: rotate at 85, gear up with a positive rate, climb at 105. Slow
  below 152 before gear and flaps. Approach at 100, over the fence at 90.
- Landing at more than about 800 feet per minute, or with more than 25
  degrees of bank, breaks the aeroplane. Under 150 is a greaser.
