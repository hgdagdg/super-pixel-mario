# Super Pixel Mario

Optimized **2D canvas platformer** inspired by classic side-scrollers. Built **entirely remotely** via GitHub MCP (no local project checkout) and hosted on **Vercel**.

## Play

- **Move:** Arrow keys / A D  
- **Jump:** Space / W / ↑  
- **Pause:** P · **Mute:** M  
- Touch buttons on mobile  

## Technical highlights

| Area | Approach |
|------|----------|
| Physics | Fixed timestep (120 Hz) + variable render |
| Rendering | Camera culling, `imageSmoothingEnabled=false` |
| Particles | Object pool (no GC spikes) |
| Audio | Web Audio API synth (zero asset downloads) |
| Deploy | Static files on Vercel edge |

## Stack

Vanilla HTML · CSS · Canvas 2D · Vercel · GitHub

## License

MIT — fan-made educational demo. Not affiliated with Nintendo.