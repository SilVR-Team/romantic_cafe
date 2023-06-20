<h1 align="center">
  <br>
  <img src="https://github.com/SilVR-Team/romantic_cafe/assets/62130211/d1dd8101-6281-486f-a05b-0fb8d3d7f9e5" alt="Markdownify" width="500">
  <br>
  SilVR - Romantic Cafe Repository
  <br>
</h1>

<h2>Environment</h2>
<p>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/subversion-%23809CC9.svg?style=for-the-badge&logo=subversion&logoColor=white">
  <img src="https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white">
</p>

<h2>Stack</h2>
<p>
  <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white">
</p>

<h2>Communication</h2>
<p>
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=blue">
  <img src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white">
  <img src="https://img.shields.io/badge/kakaotalk-FFCD00?style=for-the-badge&logo=kakaotalk&logoColor=black">
</p>

<h2>SilVR Demo Video</h2>
<h1 align="center">
  <br>
  <a href="https://www.youtube.com/watch?v=0CKSVu-vAFc">
    <img src="http://img.youtube.com/vi/0CKSVu-vAFc/0.jpg" alt="SilVR Demo" width="500">
  </a>
</h1>
<hr>

<div>
  <h2 align="center">Index</h2>
  <p align="center">
    <a href="#project-feature">Project Features</a> /
    <a href="#requirements">Requirements</a> /
    <a href="#documents">Documents</a> /
    <a href="#how-to-start">How to Start</a> /
    <a href="#assets">Assets</a> /
    <a href="#detailed-layout">Detail Layout</a> /
    <a href="#contributor">Contributor</a> / 
    <a href="#how-to-contribute">How To Contribute</a> 
  </p>
<div>

<hr>

## Project Features

- Player Character
    - Data Save & Load
    - Input Action
    - Collision Movement
- Player Movement
    - Teleport
    - Smooth Locomotion
- Player Interaction
    - Grab
        - Snap
        - Free
    - Collision Touch
- Fluid Calculation
    - Total Fluid Amount
    - Fluid Movement
    - Fluid Mixing
- Fluid Discrimination/Representation
    - Niagara Particle
    - RealLiquidX
- Compendium
- Café Music Player
    - Volume Control
    - Play / Pause
    - Next / Previous
- Tutorial / Recipe Tablet
- Order System
    - Create NPC
    - Display Order
- NPC
    - Order
- Coffee Making Tools
    - Espresso Machine
    - Coffee Grinder
    - Tamper / Tamping Mat
    - Milk Steamer
    - Whipper
- Reset Area

## Requirements
  - A Windows PC with nice graphics card(s). NVIDIA GTX 980 or better is recommended.
  - Unreal Engine 5.1.1
      - [Unreal Engine Programming Guide](https://docs.unrealengine.com/5.1/ko/unreal-engine-programming-and-scripting/)
      - [Unreal Engine API Reference](https://docs.unrealengine.com/5.1/en-US/API/)
  - Oculus Quest 2

## Documents

- [SilVR - VR Cafe Simulator Developer Documentation](https://docs.google.com/document/d/1o74CEwEUOsszbGsvd2OjO9if7JbkqsqSqR9cja5UCIA/edit?usp=sharing)
- [SilVR - VR Cafe Simulator User Documentation](https://docs.google.com/document/d/1DQbe0XPyp8OsYdHnKbTf6dIVP5Zr6BxDDbZMLYCZ7Sg/edit?usp=sharing)

## How to Start

To start using the released files, follow these steps:

1. Download the latest release from the [Releases](https://github.com/SilVR-Team/romantic_cafe/releases) page.

2. Extract the downloaded ZIP file to your desired location on your computer.

3. Open the extracted folder.

4. Double-click on the executable file ('SilVR.exe`) to launch the application.

   > Note: Make sure to have Unreal Engine 5.1.X or a compatible version installed on your computer before running the application.

5. Follow the on-screen instructions or refer to the in-app documentation to learn how to navigate and interact with the Romantic Cafe project.

6. Enjoy exploring and experiencing the Romantic Cafe virtual environment!

## Assets

- [Real Liquid X - Liquid Material & Blueprint](https://www.unrealengine.com/marketplace/ko/product/real-liquid-x-liquid-material-blueprint?sessionInvalidated=true)

### + Demo Video

- [VP Real Food and Coffee Bakery](https://www.unrealengine.com/marketplace/ko/product/vp-real-food-and-coffee-bakery)
- [Scanned 3D People Pack](https://www.unrealengine.com/marketplace/en-US/product/9c3fab270dfe468a9a920da0c10fa2ad?sessionInvalidated=true)
- [ActorCore Sample Motions](https://www.unrealengine.com/marketplace/en-US/product/actorcore-daily-motion)

## Detailed Layout
In this project, Comment Colors are used to differentiate the purpose of blueprints used in the template based on which parts of the code they are involved in. Aligning with the existing color key can help in better understanding the project. The color key used in the project is as follows:

|                               Color                               | Purpose                     |
|:-----------------------------------------------------------------:|-----------------------------|
|  ![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)  | Manipulation / Interaction  |
|  ![#00FFFF](https://via.placeholder.com/15/00FFFF/000000?text=+)  | Basic Setup                 |
|  ![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)  | Fluid System                |
|  ![#FFA500](https://via.placeholder.com/15/FFA500/000000?text=+)  | Particle / Niagara / Effect |
|  ![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)  | Save / Load                 |
|  ![#FFFF00](https://via.placeholder.com/15/FFFF00/000000?text=+)  | Sound                       |
|  ![#FF00FF](https://via.placeholder.com/15/FF00FF/000000?text=+)  | UI, Widgets                 |
|  ![#000000](https://via.placeholder.com/15/000000/000000?text=+)  | Animation                   |

## Contributor

|     | name          | main task                           | github address                 | contact                |
| --- |---------------|-------------------------------------|--------------------------------|------------------------|
|     | Euncheol Choi | NPC and Quests                      | https://github.com/dmscjf      | chober0201@gmail.com   |
|     | Jaehyun Yun   | Fluid materials and FX application  | https://github.com/ernati      | ernati@naver.com       |
|     | Jaemin Choi   | Overall system and UI, Level design | https://github.com/aelrot12    | aelrot12@hanyang.ac.kr |
|     | Yunho Choi    | Modeling and SFX application        | https://github.com/YouKnowGit  | choi15ho@gmail.com     |

## How to contribute

If you have a suggestion that would make this better, please fork the repo and create a pull request.

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request
