<div align="center">

<img src="banner.svg" alt="Maximator13: robotics, automation and web" width="100%"/>

**Engineering student at IMT Mines Alès 🇫🇷 · Robotics, autonomous systems, industrial automation & interactive software**

I build projects that mix algorithms, software engineering and real-world testing.

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

### 📜 Interactive history sites *(work in progress)*
`TypeScript` `React` `Three.js` `Vite` `Playwright` `GitHub Actions`

Three study sites built on the same stack, each organised around an interactive timeline:

| Site | Period | What's specific |
|---|---|---|
| 🏛️ **Roma** · [code](https://github.com/Maximator13/roma) · [live](https://maximator13.github.io/roma/) | 753 BC to 1453 | 3D scenes of Roman history |
| 🏺 **Hellas** · [code](https://github.com/Maximator13/hellas) · [live](https://maximator13.github.io/hellas/) | Mycenae to Cleopatra | Historical map of the Greek world + 3D scenes |
| ⚜️ **France** · [code](https://github.com/Maximator13/france) · [live](https://maximator13.github.io/france/) | Clovis (481) to Napoleon (1821) | One track per power, relief map with territories year by year (ETOPO, Natural Earth, Cliopatria), Republican calendar dates |

Each one has lint, type checking, unit tests, data validation at build time, Playwright smoke tests and automatic deployment with GitHub Actions.

### 🏭 [Flow management ERP](https://github.com/Maximator13/ERP_Pilotage_de_Flux_demo)
`HTML`

Demo of a production flow management ERP.

## 🧰 Arsenal

- **Robotics:** ROS 2, Nav2, Gazebo, TurtleBot3, coverage path planning
- **Languages:** Python, TypeScript, HTML/CSS
- **Web & 3D:** React, Three.js, Vite
- **Quality:** pytest, Playwright, ESLint, GitHub Actions
- **Tools:** Git, Linux

## 🐍 Activity

<div align="center">
<img alt="Snake eating the contribution grid" src="https://raw.githubusercontent.com/Maximator13/Maximator13/output/snake.svg" width="100%"/>
</div>

## 📱 Contact

Open to robotics and software engineering internships. Reach me through GitHub or my site: [maximator13.github.io](https://maximator13.github.io/)
