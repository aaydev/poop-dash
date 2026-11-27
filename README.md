# 💩 Poop Dash

**Poop Dash** is a fun, fast-paced arcade survival game where you control a little poop character trying to survive through 10 increasingly challenging levels and defeat the ultimate enemy — the Toilet King! 🚽👑

Collect corn, dodge obstacles, fight crazy bosses, and prove that you're the ultimate sewer survivor!

## 🎮 Game Features

- **10 unique levels** — travel through highways, forests, clouds, deserts, oceans, space, cities, lava lands, icy wastelands, and the Sewer Throne.
- **10 unique bosses** — each level ends with an individual mini-boss featuring different movement patterns and attack styles.
- **Increasing difficulty** — levels become longer and more challenging as you progress.
- **Survival mechanics** — start with 3 lives and earn an extra life after defeating each boss (up to 3 lives).
- **Collectibles** — collect 🌽 corn to earn 15 points per item.
- **Combat system** — shoot 💩 projectiles to destroy incoming obstacles and damage bosses.
- **High score tracking** — your best score is saved locally in your browser.
- **Visual effects** — particles, explosions, screen shake, flashes, and animated effects.
- **Mobile-friendly** — responsive layout with touch and pointer controls.
- **Telegram Mini App support** — integrates with Telegram Web Apps API, including theme adaptation and haptic feedback.

## 🕹️ Controls

| Action | Keyboard | Touch |
|---|---|---|
| Move left | ← or A | Move finger left |
| Move right | → or D | Move finger right |
| Shoot | Double-tap | Double-tap |
| Start / Continue | Space or Enter | Tap the button |
 
You can also move your character directly by moving the pointer across the game area.

## 🏆 How to Play

1. Start the game with 3 lives.
2. Dodge incoming obstacles and collect corn.
3. Each corn item gives you **+15 points**.
4. Survive until the level timer expires.
5. Defeat the boss using your projectile attack.
6. Complete the level to restore one life (up to the maximum of 3).
7. Continue through all 10 levels.
8. Defeat the final boss — **The Toilet King** — to win the game!

**Important:** You have only three lives at a time. Avoid collisions and use your shooting ability wisely!

## 🌍 The 10 Levels

| Level | Environment | Boss |
|---|---|---|
| 1 | Highway | 🚛 Garbage Truck |
| 2 | Forest | 🐗 Boris the Boar |
| 3 | Clouds | ⛈️ Thunderstorm |
| 4 | Desert | 🦂 Sandy the Scorpion |
| 5 | Ocean | 🦈 Joe the Shark |
| 6 | Space | 👾 Alien Poop |
| 7 | Night City | 🚁 Trash Helicopter |
| 8 | Lava Lands | 🐉 Lava Dragon |
| 9 | Frozen Wasteland | 🧊 Ice Yeti |
| 10 | Sewer Throne | 🚽 Toilet King |

## 🚀 Getting Started

Poop Dash is built as a lightweight, standalone HTML5 game. No build tools, package managers, or installation are required.

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/aaydev/poop-dash.git
   ```

2. Open the project directory:

   ```bash
   cd poop-dash
   ```

3. Open `index.html` in your web browser.

Alternatively, start a local HTTP server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

### Deployment

The game can be hosted on any static web hosting service, including:

- GitHub Pages
- Netlify
- Vercel
- Any standard web server

Simply publish the project files and make sure `index.html` is accessible.

## 🛠️ Technology

Poop Dash uses a simple, dependency-light web technology stack:

- **HTML5** — game structure.
- **CSS3** — responsive layout and interface.
- **Vanilla JavaScript** — game logic, physics, collision detection, and animations.
- **HTML5 Canvas** — real-time game rendering.
- **Telegram Web Apps API** — optional Telegram integration.
- **LocalStorage** — persistent high scores and progression data.

There is no external game engine or JavaScript framework.

## 📱 Telegram Mini App

Poop Dash includes basic Telegram Mini Apps integration.

When opened inside Telegram, the game:

- Expands to use the available viewport.
- Adapts its background and text colors to the Telegram theme.
- Disables Telegram's vertical swipe gestures when supported.
- Provides haptic feedback for important game events.

The game can also run independently in a regular web browser.

## 📂 Project Structure

```text
poop-dash/
│
├── index.html    # Main game: HTML, CSS, JavaScript
├── bg1.png       # Background image resources
├── bg2.png
├── bg3.png
├── bg4.png
├── bg5.png
├── bg6.png
├── bg7.png
├── bg8.png
├── bg9.png
└── bg10.png
```

## 🤝 Contributing

Contributions, ideas, bug reports, and suggestions are welcome!

Feel free to fork the repository, experiment with the game, and submit a pull request.

## 📄 License

No license has been specified yet. Please contact the repository owner before redistributing or using the project in other products.

---

**Made with 💩, JavaScript, and a questionable sense of humor.**

*Run, dodge, collect corn, defeat bosses — and never trust a toilet!* 🚽
