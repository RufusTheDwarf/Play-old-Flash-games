<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:120000,30:5C0000,65:B5121B,100:FF4D00&height=220&section=header&text=FLASH%20ARCHIVE&fontSize=48&fontColor=FFFFFF&fontAlignY=36&desc=THE%20GOLDEN%20AGE%20OF%20BROWSER%20GAMING&descSize=13&descAlignY=58&animation=fadeIn" width="100%" alt="Flash Archive banner" />

<br>

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=11&duration=3000&pause=1000&color=FF4D4D&center=true&vCenter=true&width=700&height=40&lines=INSERT+COIN+TO+CONTINUE;LOADING+FLASH+MEMORIES...;WELCOME+BACK+TO+2005." alt="Retro animated text" />

<br>

**A collection dedicated to preserving and rediscovering classic Flash games.**

Explore archived SWF files, run them with Ruffle and revisit the games that shaped the early Internet.

<br>

[![Archive](https://img.shields.io/badge/PROJECT-FLASH%20ARCHIVE-E63946?style=for-the-badge)](#game-library)
[![Emulator](https://img.shields.io/badge/EMULATOR-RUFFLE-FF6B35?style=for-the-badge&logo=rust&logoColor=white)](https://ruffle.rs/)
[![Format](https://img.shields.io/badge/FORMAT-SWF-9D0208?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/LICENSE-CC0%201.0-6A040F?style=for-the-badge)](LICENSE)

<br>

[![Stars](https://img.shields.io/github/stars/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash?style=flat&color=FFB703)](https://github.com/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash/stargazers)
[![Forks](https://img.shields.io/github/forks/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash?style=flat&color=E63946)](https://github.com/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash/forks)
[![Watchers](https://img.shields.io/github/watchers/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash?style=flat&color=FF6B35)](https://github.com/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash/watchers)
[![Issues](https://img.shields.io/github/issues/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash?style=flat&color=E63946)](https://github.com/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash/issues)
[![Last Commit](https://img.shields.io/github/last-commit/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash?style=flat&color=9D0208)](https://github.com/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash/commits/main)
[![Repo Size](https://img.shields.io/github/repo-size/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash?style=flat&color=6A040F)](https://github.com/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash)
[![License](https://img.shields.io/badge/CONTENT-PRESERVATION-FF4D00?style=flat)](LICENSE)

<br>

<a href="#about">ABOUT</a> ・
<a href="#game-library">GAME LIBRARY</a> ・
<a href="#installation">INSTALLATION</a> ・
<a href="#how-to-play">HOW TO PLAY</a> ・
<a href="#resources">RESOURCES</a>

</div>

---

## `01` / About

Remember the days when opening a browser meant discovering hundreds of small games?

Before modern gaming platforms, Flash games were everywhere. Racing games, platformers, shooters, strategy games, physics experiments and strange little animations were part of everyday Internet culture.

**Flash Archive** is a personal preservation project dedicated to rediscovering that era.

The repository brings together:

- Preserved `.swf` game files.
- Ruffle, an open-source Flash emulator.
- Screenshots and game-related material.
- Installation guides for different operating systems.
- References to other digital preservation projects.

The idea is simple: keep old games accessible without depending on the discontinued Adobe Flash Player.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=120000&height=3&section=header" width="75%" alt="Red divider" />

<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=14&duration=3500&pause=1000&color=FF6B35&center=true&vCenter=true&width=550&height=32&lines=THE+GAMES+ARE+STILL+HERE.;THE+MEMORIES+ARE+STILL+HERE.;PRESS+START." alt="Archive animation" />

</div>

## `02` / The Flash era

Adobe Flash Player powered a large part of the web for many years.

It allowed websites to display interactive animations, games and multimedia content through the SWF format.

However, Flash eventually became outdated as modern web standards developed.

| Date | Event |
|---|---|
| December 31, 2020 | Adobe ended Flash Player support |
| January 12, 2021 | Adobe blocked Flash content from running in Flash Player |
| Today | Emulation and preservation projects keep old content accessible |

### Why not use the original Flash Player?

Adobe no longer provides security updates for Flash Player and recommends uninstalling it.

Using old or unofficial Flash Player installers can expose your computer to security risks.

This project therefore recommends using **Ruffle** instead.

Reference: [Adobe Flash Player End of Life](https://www.adobe.com/support/flashplayer/)

## `03` / Ruffle emulator

<div align="center">

<a href="https://ruffle.rs/">
<img src="https://ruffle.rs/logo.svg" width="180" alt="Ruffle logo" />
</a>

<br>

[![Ruffle Release](https://img.shields.io/github/v/release/ruffle-rs/ruffle?style=flat&label=Latest%20release&color=E63946)](https://github.com/ruffle-rs/ruffle/releases)
[![Rust](https://img.shields.io/badge/BUILT%20WITH-RUST-FF6B35?style=flat&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Open Source](https://img.shields.io/badge/PROJECT-OPEN%20SOURCE-9D0208?style=flat&logo=github&logoColor=white)](https://github.com/ruffle-rs/ruffle)

</div>

[Ruffle](https://ruffle.rs/) is an open-source Flash Player emulator written in Rust.

It recreates the Flash environment and allows SWF content to run on modern desktop systems and in web browsers through WebAssembly.

### Why Ruffle?

| Feature | Description |
|---|---|
| Open source | Public source code and community development |
| Cross-platform | Windows, macOS and Linux desktop builds |
| Browser support | Flash content can run in compatible modern browsers |
| No Adobe Flash Player | Uses its own emulation implementation |
| Active development | Compatibility continues to improve |

### Compatibility

Ruffle supports ActionScript 1, 2 and 3, but its implementation is still evolving.

Some games may contain unsupported features, visual glitches, audio problems or other compatibility issues.

Check the official [Ruffle compatibility page](https://ruffle.rs/compatibility) when a game does not work correctly.

Official downloads: [ruffle.rs/downloads](https://ruffle.rs/downloads/)

## `04` / Game library

The current collection focuses on the **Road of Fury** series and its associated files.

<div align="center">

### ROAD OF FURY

<img src="games/Road_Of_Fury/roadoffury1-menu.png" width="85%" alt="Road of Fury main menu" />

<sub>Original game menu</sub>

</div>

### Available games

| Game / File | Description | Size |
|---|---|---:|
| [Road of Fury](games/Road_Of_Fury/Road_of_Fury.swf) | Original SWF file | 3.6 MB |
| [Road of Fury 2](games/Road_Of_Fury/roadoffury2.swf) | Second game version | 6.5 MB |
| [Road of Fury 2, December build](games/Road_Of_Fury/RoF2_23Dec.swf) | Additional build | 6.5 MB |
| [RoadZ](games/Road_Of_Fury/RoadZ.swf) | Additional SWF file | 5.0 MB |

Some files also exist under their original archive filenames. Identical copies have been retained where useful for preserving the source archive structure.

### Game screenshots

<div align="center">

<table>
<tr>
<td align="center" width="50%">
<img src="games/Road_Of_Fury/roadoffury1-gameplay1.png" width="100%" alt="Road of Fury gameplay screenshot" />
<br>
<strong>Road of Fury</strong>
<br>
<sub>Gameplay</sub>
</td>
<td align="center" width="50%">
<img src="games/Road_Of_Fury/roadoffury1-gameplay2.jpg" width="100%" alt="Road of Fury gameplay screenshot 2" />
<br>
<strong>Road of Fury</strong>
<br>
<sub>Gameplay</sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
<img src="games/Road_Of_Fury/roadoffury2-menu.png" width="100%" alt="Road of Fury 2 menu" />
<br>
<strong>Road of Fury 2</strong>
<br>
<sub>Main menu</sub>
</td>
<td align="center" width="50%">
<img src="games/Road_Of_Fury/roadoffury2-gameplay1.png" width="100%" alt="Road of Fury 2 gameplay" />
<br>
<strong>Road of Fury 2</strong>
<br>
<sub>Gameplay</sub>
</td>
</tr>
</table>

</div>

The game directory also contains additional screenshots, credits and archive metadata.

## `05` / Installation

Ruffle is available for Windows, macOS and Linux.

[![Download Ruffle](https://img.shields.io/badge/DOWNLOAD-RUFFLE-E63946?style=for-the-badge&logo=github&logoColor=white)](https://ruffle.rs/downloads/)

### Windows

This repository includes a Windows Ruffle executable and an MSI installer inside the `Ruffle/` directory.

**Option A: Use the included executable**

1. Open the repository folder.
2. Enter the `Ruffle/` directory.
3. Launch `ruffle.exe`.
4. Select a SWF file.
5. Start playing.

**Option B: Download a fresh version**

1. Visit the [official Ruffle downloads page](https://ruffle.rs/downloads/).
2. Download the Windows desktop version.
3. Extract the archive.
4. Launch Ruffle.
5. Open your SWF file.

The bundled version may be older than the current release. Check the official page for updates.

### macOS

1. Visit the [official Ruffle downloads page](https://ruffle.rs/downloads/).
2. Download the macOS desktop build.
3. Extract the archive.
4. Open Ruffle.
5. Select your SWF file.

### Linux

1. Visit the [official Ruffle downloads page](https://ruffle.rs/downloads/).
2. Select the appropriate Linux build for your architecture.
3. Extract the archive.
4. Follow the included instructions.
5. Launch Ruffle with your SWF file.

For more information, consult the [Ruffle documentation](https://github.com/ruffle-rs/ruffle/wiki).

## `06` / How to play

Once Ruffle is installed, you can launch a game using several methods.

### Method 1: Open a file

1. Start Ruffle.
2. Select **Browse** or **Open File**.
3. Navigate to the game folder.
4. Select your `.swf` file.
5. Start playing.

### Method 2: Drag and drop

1. Open the Ruffle desktop application.
2. Drag a SWF file into the window.
3. The game should load automatically.

### Method 3: Command line

**Windows**

```powershell
.\Ruffle\ruffle.exe .\games\Road_Of_Fury\Road_of_Fury.swf
```

**Linux / macOS**

```bash
ruffle ./games/Road_Of_Fury/Road_of_Fury.swf
```

The Linux and macOS example assumes that Ruffle is available in your PATH. Otherwise, use the actual path to the executable.

### Method 4: Browser demo

Ruffle also provides an online demo that can load local SWF files.

1. Open the [Ruffle Web Demo](https://ruffle.rs/demo/).
2. Select the SWF file from your computer.
3. Wait for the emulator to load the game.

No Adobe Flash Player installation is required.

## `07` / Discover more games

Ruffle is an emulator, not a game collection. You need to obtain SWF files separately.

These projects help preserve and document old browser games.

| Project | Description | Website |
|---|---|---|
| Internet Archive | Preserved Flash software and games | [Flash collection](https://archive.org/details/softwarelibrary_flash) |
| Flashpoint Archive | Digital game preservation project | [Official website](https://flashpointarchive.org/) |
| Newgrounds | Original games and animations | [Newgrounds](https://www.newgrounds.com/) |

### Ruffle vs Flashpoint

These projects serve different purposes.

| Ruffle | Flashpoint |
|---|---|
| Flash emulator | Game preservation platform |
| Runs SWF content | Organizes and launches preserved games |
| Desktop and browser support | Dedicated desktop application |
| Does not provide a complete game library | Provides a large curated collection |

Flashpoint also documents how games can be preserved and contributed to its archive.

More information: [Flashpoint FAQ](https://flashpointarchive.org/faq)

**Copyright:** An old game is not automatically free to redistribute. Always check the rights and licensing conditions before sharing game files.

## `08` / Troubleshooting

| Problem | Possible cause | Suggested solution |
|---|---|---|
| Black screen | Unsupported SWF feature | Check Ruffle compatibility |
| Game does not start | Unsupported ActionScript feature | Try another build or Ruffle release |
| Missing images or sounds | External assets are missing | Keep the original game files together |
| No keyboard input | The player window is not focused | Click inside the game window |
| No sound | Audio compatibility or system settings | Check audio settings |
| Game freezes | Emulator limitation or corrupted SWF | Try another SWF version |
| Multiplayer does not work | Original server is no longer available | Check for a preservation project |

Useful support pages:

- [Ruffle compatibility](https://ruffle.rs/compatibility)
- [Ruffle issue tracker](https://github.com/ruffle-rs/ruffle/issues)
- [Ruffle Wiki](https://github.com/ruffle-rs/ruffle/wiki)

## `09` / Repository structure

```text
Jouer-aux-anciens-jeux-Flash/
│
├── README.md
├── LICENSE
│
├── Ruffle/
│   ├── ruffle.exe
│   ├── setup.msi
│   ├── LICENSE.md
│   └── README-RUFFLE.md
│
└── games/
    ├── Road_Of_Fury/
    │   ├── Road_of_Fury.swf
    │   ├── roadoffury2.swf
    │   ├── RoF2_23Dec.swf
    │   ├── RoadZ.swf
    │   ├── Screenshots
    │   └── Archive metadata
    │
    └── Un autre jeu/
```

## `10` / Adding a game

Have a classic Flash game worth preserving?

Contributions and suggestions are welcome.

When adding a game, try to include:

- The original SWF file.
- Its original filename when available.
- A screenshot or preview.
- The source or archive reference.
- Version information.
- Licensing and redistribution information.

Keep each game in its own folder and preserve related files whenever possible.

Do not upload material that you do not have permission to redistribute.

## `11` / License and credits

The repository contains a **CC0 1.0 Universal** license.

This license applies to original material that the repository owner has the right to dedicate to the public domain.

It does not automatically change the copyright or licensing conditions of third-party games, screenshots, emulator binaries or other archived material.

### Credits

- **Ruffle Team:** Flash emulation and preservation.
- **Flashpoint Archive:** Game preservation.
- **Internet Archive:** Digital preservation.
- **Original game developers:** For creating the games that made the Flash era memorable.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:120000,30:5C0000,65:B5121B,100:FF4D00&height=150&section=footer&animation=fadeIn" width="100%" alt="Flash Archive footer" />

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=10&duration=3500&pause=1000&color=FF6B35&center=true&vCenter=true&width=600&height=35&lines=THANKS+FOR+VISITING!;KEEP+THE+FLASH+ERA+ALIVE.;INSERT+COIN+TO+PLAY+AGAIN." alt="Animated footer text" />

<br>

### FLASH ARCHIVE

**Preserving games. Keeping memories alive.**

<br>

[![GitHub](https://img.shields.io/badge/GITHUB-RUFUSTHEDWARF-181717?style=flat&logo=github&logoColor=white)](https://github.com/RufusTheDwarf)
[![Repository](https://img.shields.io/badge/ARCHIVE-FLASH%20GAMES-E63946?style=flat&logo=git&logoColor=white)](https://github.com/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash)
[![Star](https://img.shields.io/badge/LIKE%20THE%20PROJECT-LEAVE%20A%20STAR-FFB703?style=flat&logo=github&logoColor=black)](https://github.com/RufusTheDwarf/Jouer-aux-anciens-jeux-Flash/stargazers)

<br>

<sub>Digital nostalgia · Game preservation · 2026</sub>

<br>

**GAME OVER? NOT YET.**

</div>
