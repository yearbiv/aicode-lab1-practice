# 3D Snake

A 3D snake game in a single self-contained `index.html`. No build step, no backend,
no packages — Three.js comes from a CDN, so opening the file in a browser is enough.

**Play:** https://yearbiv.github.io/aicode-lab1-practice/

## Controls

| Key | Direction |
| --- | --- |
| `←` `→` | left / right |
| `↑` `↓` | up / down |
| `W` `S` | away from you / toward you |

The six direction keys follow whatever the view shows, so `←` is always left on screen.

| Key | |
| --- | --- |
| `C` | swap camera: free view / auto-follow |
| `0` | reset the view |
| `P` | pause |
| `R` | restart |
| `M` | start screen |

In the free view the camera follows the mouse — no clicking. Scroll to zoom,
right-drag to pan. In auto-follow the camera rides behind the snake at a fixed angle.

## Rules

- The cage is endless: slide through any wall and you come out the other side.
- Only running into your own body ends a run.
- Graze a glowing orb's aura to eat it — you grow a segment and speed up a little.
- Orbs swell as you get closer, which is how you judge depth inside the cube.
- Speed (slow / normal / fast) is chosen on the start screen.
