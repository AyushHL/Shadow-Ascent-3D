# 🗡️ Shadow-Ascent-3D
A 3D Dungeon Hunter Browser Game built with Three.js. Fight Waves, Level Up, Spend Stat Points and Raise Shadow Allies. Single HTML File, Auto-Deployed with GitHub Actions + Pages.

🎮 **Play it Live:** [Shadow Ascent 3D](https://ayushhl.github.io/Shadow-Ascent-3d/)

---

## ✨ Features

- Fully 3D dungeon arena with dynamic lighting, shadows and fog
- Wave-based combat with a **Boss every 5th wave**
- RPG progression: XP, levels, ranks (E to S) and stat points
- Four stats that change how you play: **STR, AGI, VIT, INT**
- **Shadow Allies**: raise fallen enemies to fight for you
- Skills: slash, dash (dodge), area burst and shadow rise
- Floating damage numbers, critical hits, screen shake and particle effects

---

## 🎮 Controls

Desktop with keyboard and mouse.

| Key | Action |
|---|---|
| `W` `A` `S` `D` | Move |
| Mouse | Turn the camera (click once to lock the mouse) |
| Left click / `Space` | Slash |
| `Shift` | Dash and dodge (brief invulnerability) |
| `Q` | Shadow Burst: area attack (30 mana) |
| `E` | Rise: turn a fallen enemy into a shadow ally (25 mana) |
| `1` `2` `3` `4` | Spend stat points on STR / AGI / VIT / INT |
| `←` `→` | Turn the camera (if mouse lock doesn't work) |
| `Esc` | Pause |

---

## 📈 Stats

| Stat | Effect |
|---|---|
| **STR** | More attack damage |
| **AGI** | Faster movement and attacks, higher crit chance, shorter dash cooldown |
| **VIT** | More max health |
| **INT** | More max mana, faster mana regen, stronger shadows, more shadow slots |

Each level-up gives **3 stat points**, fully restores health and mana, and makes you a bit stronger than the last wave.

---

## 🌑 How shadows work

1. Defeat an enemy and it leaves a glowing purple mark on the floor.
2. Stand close to it and press `E`.
3. A shadow ally rises and fights for you. Stronger enemies, and bosses, make stronger shadows.
4. Your shadow limit starts at 2 and grows as you invest in INT.

---

## 🚀 Run locally

Just open the file in a browser:

```bash
git clone https://github.com/AyushHL/shadow-ascent.git
cd shadow-ascent
# open index.html (or shadow-ascent.html) in your browser
```

An internet connection is needed because Three.js and the fonts load from a CDN.

---

## ⚙️ CI/CD

Every push to `main` runs a GitHub Actions pipeline (`.github/workflows/deploy.yml`):

1. **CI**: Runs HTML, JS and CSS linting
2. **Build**: Packages the site into a `dist` folder
3. **Deploy**: Publishes it to GitHub Pages

Pull requests run CI and build only, with no deploy.

To enable deployment on your own fork, go to **Settings → Pages** and set **Source** to **GitHub Actions**.

---

## 🛠️ Tech stack

- [Three.js](https://threejs.org/) (r128) for 3D rendering
- Vanilla JavaScript, HTML and CSS
- GitHub Actions and GitHub Pages

---

## 📌 Notes

- Designed for desktop browsers (keyboard and mouse). Touch controls are not supported yet.
- Shadow Ascent is an original fan-inspired project. The characters, monsters and designs are original.

---

## 🗺️ Roadmap

- [ ] Sound effects and music
- [ ] More enemy types
- [ ] Skill tree
- [ ] Touch controls for mobile
- [ ] Local high score

---

## 📄 License

MIT. Free to use, modify and share.
