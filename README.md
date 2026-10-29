<div align="center">

<img src="banner.svg" alt="Maximator13: robotics, automation and web" width="100%"/>

**Engineering student at IMT Mines Alès 🇫🇷 · Looking for an engineering position from September 2027**

Robotics, control systems, testing & qualification. I write software to build, measure and prove things.

<sub>🇬🇧 Profile in English · 🇫🇷 Project docs in French</sub>

</div>

---

## 🗺️ Missions

### 🤖 [Autonomous vacuum robot (ROS 2)](https://github.com/Maximator13/robot-aspirateur-ros2)
`Python` `ROS 2 Humble` `Nav2` `Gazebo` `TurtleBot3`

A TurtleBot3 Burger has to cover the free floor of a room, first in Gazebo and then on the real robot with its LiDAR. Two strategies are compared with the same coverage metric: random "bump and turn" vs a boustrophedon sweep planned on the map. Built solo in 12 h for an engineering course.

- Coverage planning in pure Python (reachable-area mask, boustrophedon, coverage measurement), wrapped in ROS 2 nodes
- Waypoint follower for the real robot, Nav2 in simulation
- pytest tests for the pure Python modules, CSV logs of every run, plotting script
- Architecture, flowcharts, results and known limits documented in [`docs/`](https://github.com/Maximator13/robot-aspirateur-ros2/tree/main/docs)

### 🌿 Plant Care · [code](https://github.com/Maximator13/plant-care) · [live](https://plant-care-nine-olive.vercel.app)
`TypeScript` `Next.js` `PostgreSQL` `Vercel` `PWA`

Watering tracker for indoor and outdoor plants with a Provençal watercolour look. Each plant's next watering date comes from a deterministic formula: species interval × season × local weather (ET0 evapotranspiration from Open-Meteo). Open to anyone: sign up and try it.

- Built-in catalogue of 145 plants with SVG watercolour illustrations, photo identification with Pl@ntNet
- Rule-based advice and alerts (frost, heatwave, rain counted as watering), daily background workflow with Vercel Cron
- Web Push notifications sent by the site, installable PWA on iPhone and Android
- Auth with Clerk, Drizzle + Neon Postgres, CSP and hardened headers, per-user API quotas, black-box security probe (26 checks)

### 📜 Interactive history sites *(work in progress)*
`TypeScript` `React` `Three.js` `Vite` `Playwright` `GitHub Actions`

Three study sites built on the same stack, each organised around an interactive timeline:

| Site | Period | What's specific |
|---|---|---|
| 🏛️ **Roma** · [code](https://github.com/Maximator13/roma) · [live](https://maximator13.github.io/roma/) | 753 BC to 1453 | 3D scenes of Roman history |
| 🏺 **Hellas** · [code](https://github.com/Maximator13/hellas) · [live](https://maximator13.github.io/hellas/) | Mycenae to Cleopatra | Historical map of the Greek world + 3D scenes |
| ⚜️ **France** · [code](https://github.com/Maximator13/france) · [live](https://maximator13.github.io/france/) | Clovis (481) to Napoleon (1821) | One track per power, relief map with territories year by year (ETOPO, Natural Earth, Cliopatria), Republican calendar dates |

Each one has lint, type checking, unit tests, data validation at build time, Playwright smoke tests and automatic deployment with GitHub Actions.

## 🧰 Arsenal

<div align="center">

**Engineering**

<img src="https://skillicons.dev/icons?i=py" width="48" alt="Python" title="Python">
<img src="https://skillicons.dev/icons?i=ros" width="48" alt="ROS 2" title="ROS 2">
<img src="https://skillicons.dev/icons?i=linux" width="48" alt="Linux" title="Linux">
<img src="https://skillicons.dev/icons?i=git" width="48" alt="Git" title="Git">
<img src="https://skillicons.dev/icons?i=githubactions" width="48" alt="GitHub Actions" title="GitHub Actions">
<img src="https://skillicons.dev/icons?i=blender" width="48" alt="Blender" title="Blender">

<sub>Nav2 · Gazebo · TurtleBot3 · pytest</sub>

**Web & software**

<img src="https://skillicons.dev/icons?i=ts" width="48" alt="TypeScript" title="TypeScript">
<img src="https://skillicons.dev/icons?i=js" width="48" alt="JavaScript" title="JavaScript">
<img src="https://skillicons.dev/icons?i=html" width="48" alt="HTML" title="HTML">
<img src="https://skillicons.dev/icons?i=css" width="48" alt="CSS" title="CSS">
<img src="https://skillicons.dev/icons?i=react" width="48" alt="React" title="React">
<img src="https://skillicons.dev/icons?i=nextjs" width="48" alt="Next.js" title="Next.js">
<img src="https://skillicons.dev/icons?i=threejs" width="48" alt="Three.js" title="Three.js">
<img src="https://skillicons.dev/icons?i=vite" width="48" alt="Vite" title="Vite">
<img src="https://skillicons.dev/icons?i=tailwind" width="48" alt="Tailwind CSS" title="Tailwind CSS">
<img src="https://skillicons.dev/icons?i=nodejs" width="48" alt="Node.js" title="Node.js">
<img src="https://skillicons.dev/icons?i=postgres" width="48" alt="PostgreSQL" title="PostgreSQL">
<img src="https://skillicons.dev/icons?i=vercel" width="48" alt="Vercel" title="Vercel">

<sub>Playwright · ESLint · Drizzle · Clerk</sub>

</div>

## 🐍 Activity

<div align="center">
<img alt="Snake eating the contribution grid" src="https://raw.githubusercontent.com/Maximator13/Maximator13/output/snake.svg" width="100%"/>
</div>

## 📱 Contact

Looking for an engineering position from September 2027. Reach me through GitHub or my site: [maximator13.github.io](https://maximator13.github.io/)
