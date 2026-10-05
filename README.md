# 🗡️ Shadow-Ascent-3D
A 3D Dungeon Hunter Browser Game built with Three.js. Fight Waves, Level Up, Spend Stat Points and Raise Shadow Allies. Single HTML File, Auto-Deployed with GitHub Actions + Pages.

🎮 **Play it Live:** [Shadow Ascent 3D](https://ayushhl.github.io/Shadow-Ascent-3D/)

---

## ✨ Features

- Fully 3D Dungeon Arena with Dynamic Lighting, Shadows and Fog
- Wave-based Combat with a **Boss every 5th Wave**
- RPG Progression: XP, Levels, Ranks (E to S) and Stat Points
- Four Stats that change How you Play: **STR, AGI, VIT, INT**
- **Shadow Allies**: Raise Fallen Enemies to Fight for You
- Skills: Slash, Dash (Dodge), Area Burst and Shadow Rise
- Floating Damage Numbers, Critical Hits, Screen Shake and Particle Effects

---

## 🎮 Controls

Desktop with Keyboard and Mouse.

| Key | Action |
|---|---|
| `W` `A` `S` `D` | Move |
| Mouse | Turn the Camera (Click once to Lock the Mouse) |
| Left click / `Space` | Slash |
| `Shift` | Dash and Dodge (Brief Invulnerability) |
| `Q` | Shadow Burst: Area Attack (30 mana) |
| `E` | Rise: Turn a Fallen Enemy into a Shadow Ally (25 mana) |
| `1` `2` `3` `4` | Spend Stat Points on STR / AGI / VIT / INT |
| `←` `→` | Turn the Camera (If Mouse Lock Doesn't Work) |
| `Esc` | Pause |

---

## 📈 Stats

| Stat | Effect |
|---|---|
| **STR** | More Attack Damage |
| **AGI** | Faster Movement and Attacks, Higher Crit Chance, Shorter Dash Cooldown |
| **VIT** | More Max Health |
| **INT** | More Max Mana, Faster Mana Regen, Stronger Shadows, More Shadow Slots |

Each Level Up gives **3 Stat Points**, Fully Restores Health and Mana, and Makes you a bit Stronger than the Last Wave.

---

## 🌑 How Shadows Work

1. Defeat an Enemy and it Leaves a Glowing Purple Mark on the Floor.
2. Stand Close to it and Press `E`.
3. A Shadow Ally Rises and Fights for You. Stronger Enemies, and Bosses, Make Stronger Shadows.
4. Your Shadow Limit Starts at 2 and Grows as You Invest in INT.

---

## 🚀 Run locally

Just Open the File in a Browser:

```bash
git clone https://github.com/AyushHL/Shadow-Ascent-3D.git
cd Shadow-Ascent-3D
# Open index.html in Your Browser
```

An Internet Connection is Needed because Three.js and the Fonts Load from a CDN.

---

## ⚙️ CI/CD

Every Push to `main` Runs a GitHub Actions Pipeline (`.github/workflows/ci-cd.yml`):

1. **CI**: Runs HTML, JS and CSS linting
2. **Build**: Packages the site into a `dist` folder
3. **Deploy**: Publishes it to GitHub Pages

To Enable Deployment on Your Own Fork, Go to **Settings → Pages** and Set **Source** to **GitHub Actions**.

---

## 🛠️ Tech stack

- [Three.js](https://threejs.org/) (r128) for 3D Rendering
- Vanilla JavaScript, HTML and CSS
- GitHub Actions and GitHub Pages

---

## 📌 Notes

- Designed for Desktop Browsers (Keyboard and Mouse). Touch Controls are not Supported Yet.
- Shadow Ascent is an Original Fan-inspired Project. The Characters, Monsters and Designs are Original.

---

## 🗺️ Roadmap

- [ ] Sound Effects and Music
- [ ] More Enemy Types
- [ ] Skill Tree
- [ ] Touch Controls for Mobile
- [ ] Local High Score

---

## 📄 License

MIT. Free to Use, Modify and Share.
