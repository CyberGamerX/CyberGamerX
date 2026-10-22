# Personal Overview
I am a Mechatronic Systems Engineering student, studying at Simon Fraser University as well as a graduate of the Television and Video Production program and the British Columbia Institute of Technology.

I have been developing games and programming for 7 years, primarily in the Unity Game Engine. I primarily participate in Game Jams with Blueberry Jam Games, though I have also worked on longer term projects such as [Travelling Merchant](https://github.com/Blueberry-Jam-Games/Travelling-Merchant) (*Working Title*).

Please note that the projects listed below are not exaustive. Smaller projects are present within my github account and several projects do not have repositories at this time.

I, along with Blueberry Jam Games have published several projects from game jams on [Itch](https://cybergamerx.itch.io/) linked below.

I primarily work as a programmer and technical artist on projects, though I have been the project lead during a few jams. Of particular note would be GMTK 2025 where we entered the game [OuroTorus](https://github.com/Blueberry-Jam-Games/GMTK-2025) in which I was the lead programmer and team lead.

### Known Programming Languages
|  |  |  |  |  |
| :--- | :--- | :--- | :--- | :---: |
| C | C# | C# | C++ |
| HLSL | Python | Java | Lua | Extended Script <br> *After Effects Scripts* |

### Links
- Personal Github Account: <https://github.com/CyberGamerX/>
- Blueberry Jam Games Github: <https://github.com/Blueberry-Jam-Games>
- Personal Itch Account: <https://cybergamerx.itch.io/>

# Repository Highlights
## Travelling Merchant - *Working Title*
### About
Travelling Merchant is a solo project that I am currently developing in Unity utilizing ECS, Unity DOTS (*Data Oriented Technology Stack*) to and compute shaders to provide as much performance optimization as possible.

The game will see a player playing as a travelling trader moving from town to town buying and selling wares. Unlike other games of this genre however, every item is physical and must be somehow carried by the player. This can be a bag, on horseback or carriage, but regardless all items are physicsal.

The map the player traverses is procedural and seed based allowing for replayability.

Currently, the procedural world is in an early test stage with chunk generation fully function and a linear path being generated for the player to follow. The world is created using the Marching Cubes algorithm run on Compute Shaders and individual chunk placement is handled by several ECS Systems and components. The game has maintained 60fps on a GTX 1060 and 6 core CPU demonstrating the current optimizations present.

This is a personal project targeted at improving my performance sensitive programming as well as learning new skills such as ECS and Compute Shaders. In addition I am also working on learning Unity's Scriptable Rendering Pipeline in depth so that I can write my own post processing shaders in the future.

An early version of this can be seen with a variation on the Kuwahara Filter (*Oil Paint Filter*) that is able to edge detect for stable visuals while moving and an outline shader that utilizes a 3d vertex shader to create misaligned outlines that are stable while moving. The intent of this is to create an oil painted look on distant terrain. 

#### Gameplay Photo
![Gameplay Photo](Travelling%20Merchant%201.png)

#### Chunk Generation Debug View
![Chunk Generation](Travelling%20Merchant%202.png)

### Links
- Github: <https://github.com/Blueberry-Jam-Games/Travelling-Merchant>

## OuroTorus
### About
OuroTorus was made for the 2025 GMTK Game Jam alongside a team of artists, programmers and writers under the brand of Blueberry Jam Games. All assets and programming were done during the jam which lasted for 96 hours.

This game is my most recent game project which I was the team lead for and one of the more technically complex ones we have executed. All movement is handled with polar coordinates and all models around the Torus, or Donut are deformed to always line up correctly solving the largest issue with level design on a torus.

#### Title Screen
![Ouro Torus Title Screen](OuroTorus%201.png)

#### Gameplay Photo
![Ouro Torus Sample Gameplay](OuroTorus%202.png)

### Links
- Github: <https://github.com/Blueberry-Jam-Games/GMTK-2025>
- Itch: <https://cybergamerx.itch.io/ourotorus>

## Shadowcast
### About
Shadowcast was created for the 2024 GMTK Game Jam by Blueberyy Jam Games. I took on the role of technical artist during the development of this game as well as assiting in the coordination of art styles within the team.

The game sees the player completing a 3d platformer as well as a 2d platformer created by the players shadow. By moving the light source and moving closer and further from the light, the player can adjust the size and properties of their shadow.

All assets and character animations were done during the Jam which took place over 96 hours.

### Links
- Github: <https://github.com/Blueberry-Jam-Games/GMTK2024>
- Itch: <https://zenith08.itch.io/shadowcast>

## Camera Tracker
### About
The camera tracker project was an early test to attempt to create virtual sets for photography. Currently the system uses the 6 axis IMU on an Arduino Nano to determine rotation then transmits that data to a Unity server that can visualize that data in real time. Through the Canon EDSDK, an image could also be transmitted and synced to the rotation of the sensor.

This project has been paused since 2024 until a solution to local position tracking can be achieved at which time this project may be revisited.

### Links
- Arduino Repository: <https://github.com/CyberGamerX/Camera-Tracker-Arduino>
- Unity Repository: <https://github.com/CyberGamerX/Camera-Tracker-Unity>

# Chronological Project List

| Project Name and Repository | Year | Project Type | Playable Version |
| :--- | :--- | :--- | :--- |
| [Travelling Merchant](https://github.com/Blueberry-Jam-Games/Travelling-Merchant) | 2026 | Personal Project | No Build Available |
| [Corperate Efficiency](https://github.com/Blueberry-Jam-Games/GMTK-Game-Jam-2026) | 2026 | GMTK 2026 | [itch](https://aurea01.itch.io/corporate-efficiency) |
| [Social Masquerade](https://github.com/Blueberry-Jam-Games/GGJ-2026) | 2026 | GGJ 2026 | [Itch](https://zenith08.itch.io/social-masquerade) |
| [OuroTorus](https://github.com/Blueberry-Jam-Games/GMTK-2025) | 2025 | GMTK 2025 | [itch](https://cybergamerx.itch.io/ourotorus) |
| [Camera Tracker Unity](https://github.com/CyberGamerX/Camera-Tracker-Unity) <br> [Camera Tracker Arduino](https://github.com/CyberGamerX/Camera-Tracker-Arduino) | 2024 | Personal | In Editor <br> *Prototype Only* |
| [Shadowcast](https://github.com/Blueberry-Jam-Games/GMTK2024) | 2024 | GMTK 2024 | [itch](https://zenith08.itch.io/shadowcast) |
| Family Train Conductor | 2023 - 2024 | Blueberry Jam Project | Contact for Access |
| [Cosmic Collission](https://github.com/Blueberry-Jam-Games/RollForControl) | 2023 | GGJ 2023 | [itch](https://zenith08.itch.io/cosmic-collision) |
| [Cookie Crusade](https://github.com/Blueberry-Jam-Games/GMTK-Candy-Crusher) | 2022 | GMTK 2022 | [itch](https://zenith08.itch.io/cookie-crusade) |
| [Splash Lake Waterpark](https://github.com/Blueberry-Jam-Games/BC-Game-Jam-2022) | 2022 | BC Game Jam 2022 | [itch](https://zenith08.itch.io/splash-lake-waterpark) |
| [Splintered Spectrum](https://github.com/Blueberry-Jam-Games/GMTK-2021-Temple-Crawl) | 2021 | GMTK 2021 | [itch](https://zenith08.itch.io/splintered-spectrum) |

