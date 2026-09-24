# School Bus Race — Anka Bilim Grand Prix

A 3D browser racing game about an invented motor sport: the **School Bus Race**. The school bus models seen most often on Turkish roads line up on a street circuit in Ankara. The first bus to reach Anka Bilim School wins.

**To play:** open `index.html` in Chrome, Edge, Firefox or Safari. It needs an internet connection to load the 3D engine and the fonts.

## The sport

- **What is it?** A motor sport competition for the vehicle brands most preferred as school buses. They come together and race, and the first one to reach Anka Bilim School wins.
- **The setting:** real streets and large parking lots, just like a real motor sport. The finish line is Anka Bilim School.
- **Where it began:** it was first organised by the school bus drivers' union to support bus drivers.
- **How to enter:** you only need one of the six models.

## How to play

1. Press **Start engines**, choose one of the 7 drivers, then one of the 6 buses.
2. Drive through the yellow bus stops to pick up students. Every stop fills one third of your **super power** bar.
3. When the bar is full (3 stops), press **Shift** to use your driver's super power.
4. Finish first at Anka Bilim School. Races are 1, 3 or 6 laps against Easy, Normal or Hard rivals.

| Key | Action |
|---|---|
| ↑ or W | Gas |
| ↓ or S | Brake, then reverse |
| ← → or A D | Steer |
| Space | Drift |
| Shift | Super power |
| H | Horn |
| C | Change camera |
| R | Back on track |
| P or Esc | Pause |
| M | Sound on/off |

On phones and tablets, on-screen buttons appear. A game controller works too.

## Drivers

| Driver | Passive | Super power |
|---|---|---|
| Marjinal Maganda (Volkan Aytekin) | Reverse steering: left and right are swapped | Wings: the bus flies over everyone |
| Gluten (Egemen Delikan) | Bread on the road: touch it and it's EMERGENCY! GLUTEN GLUTEN | Baguette rocket |
| TosunKovalayan (Ataberk Tosun) | Irish jig music all race long | Rainbow and gold coins, 3× speed |
| SarpDBastırma (Sarp Bayar) | The bus howls when it drifts | Dog mode: the bus turns into a dog and sprints |
| FizikCan (Doruk Can Topay) | Math break: an easy question every 15 seconds | Physics overload: terms fly everywhere, the screen shakes, 3× speed |
| YulafSütlüIceLatte (İrem Gökce) | None | Iced oat latte, 3× speed |
| CinnamonRoll (Ela Üstündağ) | None | Scream: every bus nearby is stunned for 3 seconds |

## Buses

| No. | Bus | Tagline |
|---|---|---|
| 1 | Ford Transit | Reliable. Always ahead. |
| 2 | Mercedes-Benz Sprinter | Comfort meets performance. |
| 3 | Volkswagen Crafter | Space for greater things. |
| 4 | Renault Master | Practical. Powerful. |
| 5 | Fiat Ducato | Built for people. |
| 6 | Otokar Sultan | Türkiye'nin gücü. |

Each bus has its own top speed, acceleration, handling and weight.

## How it is made

- One HTML file with no build step. The 3D graphics use [three.js](https://threejs.org/) r128, loaded from cdnjs, and every sound is generated in the browser with the Web Audio API.
- The 2.23 km circuit includes a car park section, grandstands, bus stops and Anka Bilim School at the finish line.
