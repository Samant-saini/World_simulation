# 🌿 Cozy Animal Village — A Living Pixel-Art World

A cozy, interactive pixel-art village simulation where animals and villagers live their own lives, follow daily routines, interact with each other, and experience unexpected events.

Built entirely with **HTML, CSS, and JavaScript**, this project brings a tiny living world to life — complete with a day/night cycle, autonomous characters, cozy environments, and dynamic events.

## ✨ Features

### 🌄 Living Day & Night Cycle
- Complete 24-hour simulation cycle.
- Smooth transitions between dawn, morning, afternoon, dusk, and night.
- Dynamic lighting and colour changes based on the time of day.
- Glowing lanterns, windows, fireflies, and stars at night.
- Adjustable simulation speed from 0.5x to 8x.

### 🐑 Autonomous Villagers
Every villager has their own personality, schedule, movement, and activities.

| Character | Role |
|---|---|
| Wool 🐑 | Sheep who grazes in the meadow |
| Clover 🐇 | Rabbit who explores the village |
| Rusty 🦊 | Fox who occasionally hunts hens |
| Hoot 🦉 | Owl who becomes active at night |
| Tom 👨‍🌾 | Farmer who works in the garden |
| Mira 👩 | Mother who spends time with the family |
| Pip 👦 | Kid who explores and plays |
| Lily 👧 | Kid who enjoys village activities |
| Biscuit 🐕 | Dog who follows Pip and chases other animals |

### 🕒 Daily Routines
- Villagers move between different locations throughout the day.
- Characters perform activities based on their schedules.
- Family members gather for lunch and dinner.
- Animals graze, explore, play, work, and sleep.
- Sleeping villagers disappear into their homes while little 'Z' particles float above their doors.

### 🎭 Dynamic Events
The village is not just animated — unexpected events can happen!

- 🦊 **Fox Hunt:** Rusty may sneak into the henhouse and catch a hen.
- 🐕 **Dog Chase:** Biscuit sometimes chases Wool the sheep.
- 🐑 **Sheep Escape:** Wool runs away when Biscuit starts chasing.
- 🐓 **Hen Reactions:** Hens flee into the coop when danger approaches.
- 🌲 **Fox Chase:** Biscuit can chase Rusty back towards the forest.

Events are probabilistic, making each simulated day slightly different.

### 🌳 Procedural Pixel-Art Environment
The entire world is generated programmatically without external images.

Includes:
- Hobbit-style animal burrows with pink circular doors.
- Cozy family cottage with chimney and windows.
- Henhouse and carrot garden.
- Clothesline and village decorations.
- Pond with lily pads and reeds.
- Waterfall and surrounding cliffs.
- Forest, meadow, dirt paths, and communal fire pit.
- Butterflies, grass tufts, flowers, smoke, and water effects.

### 🎮 Interactive Controls
- Play and pause the simulation.
- Jump directly to Dawn, Noon, Dusk, or Midnight.
- Scrub through the simulation timeline.
- Adjust simulation speed.
- View each villager's current activity and location.
- See whether characters are walking or performing an activity.

## 🛠️ Tech Stack

- **HTML5** — Application structure.
- **CSS3** — Dark UI, responsive layout, and pixelated rendering.
- **JavaScript** — Simulation engine, AI-like behaviour, routines, and procedural world generation.
- **HTML Canvas API** — Pixel-art rendering and animations.
- **requestAnimationFrame** — Smooth animation loop.

No external game engine or image assets are required.

## 🧠 How It Works

The simulation uses a combination of procedural generation and rule-based autonomous behaviour.

1. **World Generation:** The environment is generated using seeded randomness and rendered onto an offscreen canvas.
2. **Character Schedules:** Each villager has a daily schedule defining where they should go and what they should do.
3. **Movement System:** Characters move towards their assigned destinations.
4. **Event System:** Special events override normal routines when their conditions are met.
5. **Animation Engine:** Characters, particles, water, fire, smoke, and environmental effects are updated continuously.
6. **Lighting System:** The scene changes dynamically according to the simulation clock.

## 🚀 Getting Started

No installation or build process is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/cozy-animal-village.git
   ```

2. Open the project folder.

3. Open the HTML file in your browser:

   ```bash
   # Linux
   xdg-open index.html
   ```

   Or simply double-click `index.html`.

## 📁 Project Structure

```text
cozy-animal-village/
│
├── index.html       # Complete simulation
└── README.md        # Project documentation
```

## 🎨 Design Philosophy

The goal is to create a small world that feels alive even when nobody is controlling it.

Instead of simply animating characters, the simulation gives each villager a routine, a destination, and opportunities to interact with others.

The result is a relaxing miniature world where something interesting can happen at any moment.

## 🔮 Future Improvements

- 🌧️ Weather system with rain and storms.
- 🍂 Seasonal changes.
- 💬 Character speech bubbles and conversations.
- 🐓 Rooster that wakes the village at dawn.
- 👨‍🌾 Dad protecting the hens from the fox.
- 🔊 Ambient village sounds and music.
- 🏡 More buildings, villagers, and interactive locations.
- 🤖 AI-generated characters, stories, and behaviours.

## ❤️ Inspiration

Inspired by cozy indie games, pixel-art environments, life simulations, and the idea of creating a world where every character has a life of their own.

---

**A tiny world. A thousand little stories. 🌱**
