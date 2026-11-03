# 🌍 Procedural World Generator

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=22,11,0&height=210&section=header&text=Procedural%20World%20Generator&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Infinite%20Worlds%2C%20One%20Seed%20at%20a%20Time&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-4.1.0-2A9D8F?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Engine](https://img.shields.io/badge/Unity%20%7C%20Godot%20%7C%20WebGL-E76F51?style=for-the-badge&logo=unity&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-MIT-F4A261?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Biomes](https://img.shields.io/badge/biomes-40%2B-E9C46A?style=for-the-badge&logo=leaflet&logoColor=black)](https://github.com)

<br/>

### 🏔️ Generate infinite, unique worlds from a single seed — mountains, rivers, biomes & all

*🗺️ Seed-Based • 🌦️ Climate Simulation • 🎨 Biome Variety • ⚡ Real-Time*

<br/>

<a href="https://share.google/yvwUzO6dfMIT9PZVm">
  <img src="https://img.shields.io/badge/🚀_TRY_GENERATOR-2A9D8F?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=1E7A70" alt="Try Generator" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/yvwUzO6dfMIT9PZVm">
  <img src="https://img.shields.io/badge/📥_GET_SOURCE-E76F51?style=for-the-badge&logo=github&logoColor=white&labelColor=B8573D" alt="Get Source" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/yvwUzO6dfMIT9PZVm">
  <img src="https://img.shields.io/badge/📚_DOCS-F4A261?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=CC8A4E" alt="Docs" height="45"/>
</a>

</div>

<img width="1200" height="600" alt="image_processing20260525-2-sesmf9" src="https://github.com/user-attachments/assets/355c8090-37bc-4693-bff0-e701b41ce946" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Procedural World Generator** is a powerful, easy-to-use toolkit that creates **infinite, visually stunning worlds** from a single seed. Feed it any number, and it produces a complete landscape: continents, mountains, rivers, forests, deserts, oceans, and even climate patterns.

Built for game developers, worldbuilders, and generative art enthusiasts — ready to plug into your next game or fantasy project.

> 💡 **Perfect for:** Open-world games, tabletop RPG map generation, art projects, or just exploring — every seed is a whole new planet.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🌱 **Seed-Based** | 🗺️ **Realistic Terrain** | 🌦️ **Climate System** |
|:---:|:---:|:---:|
| Same seed = same<br/>world, every time | Mountains, valleys,<br/>rivers & erosion | Temperature, rain &<br/>biome distribution |

| 🏞️ **40+ Biomes** | 🚀 **Real-Time** | 🎨 **Export Ready** |
|:---:|:---:|:---:|
| Deserts, forests,<br/>tundras, oceans | Instant generation<br/>at any scale | PNG, heightmap,<br/>JSON & 3D meshes |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Generator

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🌍 **Truly Infinite** | Generate worlds at any zoom level — from continents down to a single valley |
| 🧬 **Deterministic** | Every seed reproduces exactly the same world — perfect for games & sharing |
| 🌦️ **Advanced Climate** | Simulates rain shadows, ocean currents & biome transitions realistically |
| ⚡ **GPU-Accelerated** | WebGL & compute shaders generate 4K world maps in milliseconds |
| 🧩 **Plug-in Ready** | Ships with Unity, Godot & vanilla WebGL adapters |
| 🎨 **Beautiful Output** | Gorgeous color palettes and shaded relief make every world pop |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 World Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🌍  Procedural World Generator  v4.1.0          ║
╠══════════════════════════════════════════════════╣
║  Seed: 48291037     Zoom: 1.0     Size: 512²     ║
║                                                  ║
║  ⛰️ ~~~🏔️~~~🌲🌲~~~🏔️~~~🌊🌊~~~🏜️🏜️~~~🌲~~~~   ║
║  🏔️🏔️🌲🌲🌲~~~🏔️🏔️~~~🌊🌊~~~🏜️🏜️🌵🌵~~~🌲🌲   ║
║  🌲🌲🌲~~~~~🏔️~~~🌊🌊🌊~~~🏜️🌵🌵~~~🌲🌲🌲🌲   ║
║  🌾🌾~~~🌳🌳~~~🌊🌊🌊~~~🏜️~~~🌳🌳~~~🌊🌊🌊   ║
║                                                  ║
║  🏔️ Mountains: 12%   🌲 Forests: 28%            ║
║  🌊 Ocean: 41%       🏜️ Deserts: 9%             ║
║  🌦️ Climate: Temperate      💧 Rivers: 47       ║
║                                                  ║
║  ⚡ 62ms generation   💾 Export ready            ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🌍 procedural-world-generator/
├── 🎯 src/
│   ├── noise/                 # Perlin & simplex noise
│   │   ├── perlin.cpp
│   │   └── simplex.cpp
│   ├── terrain/               # Heightmap & erosion
│   │   ├── heightmap.cpp
│   │   └── erosion.cpp
│   ├── climate/               # Temperature & rainfall
│   ├── biomes/                # Biome classification
│   └── render/                # Shading & coloring
├── 🖥️  shaders/               # WebGL & compute shaders
├── 🔌 integrations/           # Unity & Godot adapters
├── 🧪 tests/                  # Determinism & visual tests
└── 📖 docs/                   # API & seed reference
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)
![GLSL](https://img.shields.io/badge/GLSL-5586A4?style=for-the-badge&logo=opengl&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a weird-looking biome? Want to share your best worlds?

<div align="center">

<a href="https://share.google/yvwUzO6dfMIT9PZVm">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/yvwUzO6dfMIT9PZVm">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-2A9D8F?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/yvwUzO6dfMIT9PZVm">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-F4A261?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🌍 Made with 🏔️ by the Procedural World Team

*If this generator inspired your next world — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=22,11,0&height=120&section=footer" width="100%"/>

</div>
